# reaper parser combinator

port of [stack-expression](https://github.com/dominictarr/stack-expression) to grain-lang

WIP not ready for use.

## compile and test with docker container

```bash
docker run -it --rm -v $PWD:/root ghcr.io/grain-lang/grain:main
```

`cd` to home in docker container where the source files are mounted. then test with:

```bash
grain reaper.test.gr
```
