Windows example

```bash
docker build . -t rust_cross_compile/windows
docker run --rm -ti -v `pwd`:/app rust_cross_compile/windows
```