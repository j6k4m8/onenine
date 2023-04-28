# onenine

`onenine` is a daemon process that guarantees that your servers have precisely "one nine" of uptime. It does this by pausing docker containers on a schedule.

## Installation

```bash
pip install onenine
```

## Usage

```bash
./nine [container-id]
```

You can add more nines to the uptime:

```bash
./nine nine nine [container-id]
```

also this is a joke and i got bored and stopped implementing it when it was half done
