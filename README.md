# caps2esc

This is [caps2esc](https://gitlab.com/interception/linux/plugins/caps2esc), with an additional customized mode for myself.

## Building

```text
$ git clone https://gitlab.com/interception/linux/plugins/caps2esc.git
$ cd caps2esc
$ cmake -B build -DCMAKE_BUILD_TYPE=Release
$ cmake --build build
```

## Execution

```text
caps2esc - transforming the most useless key ever in the most useful one

usage: caps2esc [-h | [-m mode] [-t delay]]

options:
    -h        show this message and exit
    -t        delay used for key sequences (default: 20000 microseconds)
    -m mode   0: default
                 - caps as esc/ctrl
                 - esc as caps
              1: minimal
                 - caps as esc/ctrl
              2: useful on 60% layouts
                 - caps as esc/ctrl
                 - esc as grave accent
                 - grave accent as caps
```
