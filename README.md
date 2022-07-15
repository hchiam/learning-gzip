# Learning gzip [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://github.com/hchiam/learning-gzip/blob/main/LICENSE)

Just one of the things I'm learning. https://github.com/hchiam/learning

https://www.youtube.com/watch?v=NLtt4S9ErIA

```sh
gzip --version         # check that gzip runs in your CLI
gzip somefile.md       # compress to a .gz file
gzip -l somefile.md.gz # prints out compression stats (higher ratio = better)
gzip -d somefile.md.gz # decompress
```

## Further

brotli?

tar?

```sh
# to compress a folder, which gzip can't:
tar -czvf target.tar.gz somefolder
```

