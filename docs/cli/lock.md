# `mise lock`

- **Usage**: `mise lock [-f --file <FILE>]`
- **Source code**: [`src/cli/lock.rs`](https://github.com/jdx/mise/blob/main/src/cli/lock.rs)

Create a lockfile

This command creates an empty mise.lock file in the current directory.
Lockfiles are used to pin tool versions for reproducible environments.

## Flags

### `-f --file <FILE>`

The lockfile to create

Examples:

```
$ mise lock
Created lockfile mise.lock

$ mise lock --file my-project.lock
Created lockfile my-project.lock
```
