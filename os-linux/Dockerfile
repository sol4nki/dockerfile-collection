FROM ubuntu:24.04

ENV DEBIAN_FRONTEND=noninteractive

# add it if anything else is needed (ai assisted)
RUN apt-get update && apt-get install -y \
    build-essential \    # Installs gcc, g++, make, and libc-dev
    binutils \           # Installs readelf, objdump, nm, and size
    gdb \                # The GNU Debugger for step-by-step code execution
    strace \             # Tracks system calls made by a program
    ltrace \             # Tracks library calls made by a program
    valgrind \           # Memory leak and bad pointer detector
    man-db \             # Essential for looking up system calls (e.g., 'man 2 fork')
    manpages-dev \       # Developer-specific man pages for C standard library
    git \                # Version control
    curl \               # Networking tool
    vim \                # Terminal text editor (can swap for nano if preferred)
    nano \               # Simple text editor
    && rm -rf /var/lib/apt/lists/*

WORKDIR /coursework

CMD ["/bin/bash"]
