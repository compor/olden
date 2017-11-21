
# Olden benchmarks

This repo contains the source code for the [Olden][1] benchmarks taken from the LLVM test-suite subproject.

The main modifications performed in preparation for usage with [this][3] build harness were:

- move each program source to a `src` subdirectory
- remove existing build files (for `make` and `cmake`)
- move the original [README.txt][2]


Older/initial versions that were found in the interwebs were placed in archives under the `utils/archives` subdirectory.


[1]: http://www.martincarlisle.com/olden.html
[2]: README.old.txt
[3]: https://github.com/compor/sodden
