# gn build system demo

### workflow

1. write .gn file in project root

2. set `buildconfig` variable in .gn file

3. create BUILDCONFIG.gn file and set default toolchain

4. use `toolchain` function to create specific tools

5. create `BUILD.gn` file in project root


### commands

1. generate ninja file

```shell
gn gen out
```

2. generate the target

```shell
ninja -C out
```


### more

see `gn help`

```shell
gn help toolchain

gn help dotfile
```

```shell
gn help toolchain > gn_toolchain.txt
```
