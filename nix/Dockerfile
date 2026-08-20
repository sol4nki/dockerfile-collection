FROM nixos/nix:latest

WORKDIR /shared

# this was giving an error (cant install git if we have this?!?!)
RUN nix-env -e git-minimal


RUN nix-env -iA \
    nixpkgs.curl \
    nixpkgs.git \
    nixpkgs.htop \
    nixpkgs.jq \
    nixpkgs.tmux \
    nixpkgs.vim \
    nixpkgs.wget \
    nixpkgs.go \
    nixpkgs.python3 \
    nixpkgs.neovim


CMD ["bash"]

# using this for golang + python
