make sure youve built it

```docker
docker build -t os-class-env .
```

now run it whenever needed.
```
docker run -it --rm -v "$(pwd)":/coursework --cap-add=SYS_PTRACE os-class-env
```