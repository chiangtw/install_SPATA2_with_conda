# Install SPATA2 with conda

```
$ git clone https://github.com/chiangtw/install_SPATA2_with_conda.git

$ conda create -n spata2
$ conda activate spata2
(spata2)$ conda install -c conda-forge -c bioconda --file install_SPATA2_with_conda/spata2_dep.txt

(spata2)$ R
> require(devtools)
> devtools::install_github(repo = "kueckelj/confuns", dependencies = FALSE)
> devtools::install_github(repo = "theMILOlab/SPATA2", dependencies = FALSE)
...
> library(SPATA2)
```

### References

- Official website for SPATA2 (https://themilolab.github.io/SPATA2/index.html)
  - The installation page (https://themilolab.github.io/SPATA2/articles/spata-v2-installation.html)
