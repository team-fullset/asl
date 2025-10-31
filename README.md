# Macro-assembler AS by Alfred Arnold

I personally use it as a macro-assembler for Intel 8080. This is the best
multi-platform macro-assembler for Intel 8080 I've seen so far.

This fork has no functional changes from the original version and only contains
minor fixes related the compilation on MacOS.

**New**: Added support for building to Mac M1 processors (aarch64).

In order to compile via `make` you will need to copy one of the `Makefile.def` samples to `Makefile.def` in the root dir. e.g.:

```
cp Makefile.def-samples/Makefile.def-x86_64-osx ./Makefile.def
```

The project was forked from the version 1.42 build-84.

The original website -- <http://john.ccac.rwth-aachen.de:8000/as/>

Online documentation -- <http://john.ccac.rwth-aachen.de:8000/as/as_EN.html>
