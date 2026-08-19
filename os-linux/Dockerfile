FROM ubuntu:24.04

ENV DEBIAN_FRONTEND=noninteractive

# add it if anything else is needed (ai assisted)
RUN apt-get update && apt-get install -y \
    build-essential \    
    binutils \           
    gdb \                
    strace \             
    ltrace \             
    valgrind \           
    man-db \             
    manpages-dev \       
    git \                
    curl \               
    vim \                
    nano \               
    && rm -rf /var/lib/apt/lists/*

WORKDIR /coursework

CMD ["/bin/bash"]
