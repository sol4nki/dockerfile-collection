make sure youve built it

```bash
docker build -t os-class-env .
```

now run it whenever needed.
```bash
docker run -it --rm -v "$(pwd)":/coursework --cap-add=SYS_PTRACE os-class-env
```

run 
```bash
unminimize 
```
once in the system