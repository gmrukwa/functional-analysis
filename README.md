# Readme

## Installation

`tmod` package requires `XML` package, that has non-R dependency `libxml2`.
You need to install it with `apt install libxml2-dev` on debian OSes.

`DESeq2` requires:

```bash
sudo apt install libpng-dev libjpeg-dev
```

```R
BiocManager::install("DESeq2")
```
