# onenine

`onenine` is a container management tool that guarantees that your servers have precisely the right number of nines of uptime. It does this by pausing docker containers if they accidentally have too many of nine. 

onenine specializes in "downward" nine management (i.e., removing nine if there are too many); you are responsible for "upward" nine management (i.e., getting your thing to run more than desired many of nine)


## Usage

```bash
./nine [container-id]
```

You can add more nines to the uptime:

```bash
./nine nine nine [container-id]
```

also this is a joke and i got bored and stopped implementing it when it was half done
