# nix-test

## Development shell

This repository uses a Nix flake to provide a reproducible shell environment that includes `git`.

### Requirements

- Nix with flake support enabled.

### Usage

```
nix develop
```

This will drop you into a shell that has `git` available. Leave the shell with `exit`.
