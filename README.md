---
tags:
    - config
---

# pkl-playground

learn [Pkl](https://pkl-lang.org/index.html), configuration that is Programmable, Scalable, and Safe

## demo

[install](https://pkl-lang.org/main/current/pkl-cli/index.html#installation) the cli for your platform

```sh
# verify install
pkl --version

FILE=config.pkl
pkl eval $FILE
pkl eval --format json $FILE 
pkl eval --format yaml $FILE 
```

## resources

- [Pkl](https://pkl-lang.org/index.html)
- [Pkl // Docs](https://pkl-lang.org/main/current/index.html)
- [Truffle Language Implementation Framework](https://github.com/oracle/graal/tree/master/truffle) Pkl was built using the GraalVM Truffle framework