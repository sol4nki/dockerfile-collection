`golang + python`

build it (it takes so long tf)
```bash
docker build -t nix-setup .
```

run it
```bash
docker run -it --rm -v "$(pwd)/shared:/shared" nix-setup
```