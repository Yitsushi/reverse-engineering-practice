# Practice repo for reverse engineering

Random note: on MacOS, it's not `main` but `entry0`.

## v1

- strings
- `rabin2 -z` (Radare2)

### v1b

on osx you have to run radare2 with sudo to open with debug

- radare2: `db <address>` -> create a breakpoint

## v2

- `afvn local_18h something` -> rename variable `local_18` to `something`
- `VV` -> visual mode can be helpful

## v3

- Loop in a loop
- Basically the same logic to find the solution as v2 with a twist
- There is an extra check

## v4

TODO

## v5

TODO

## Radare2 help

```
rabin2 -z bin/license-v1   # aka strings
```

```
pdf                 print disassemble function
afvd                analyze function variables display
afvn <old> <new>    analyze function variables name
```
