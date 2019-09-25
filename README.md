## Sandmark Analyze

Analyse the results of [sandmark](https://github.com/ocaml-bench/sandmark/)
runs in Jupyter notebook.

## Quick start

```bash
$ git clone https://github.com/kayceesrk/sandmark-analyze
$ cd sandmark-analyze
$ docker run -v `pwd`:/analyze -p 8888:8888 -it kayceesrk/sandmark:0.1.0
$ jupyter notebook --ip=0.0.0.0 --allow-root
```
