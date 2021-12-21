# xtbiff

[![Latest Version](https://img.shields.io/badge/release-v1.1-blue)](https://github.com/grimme-lab/xtbiff/releases/latest)
[![DOI](https://img.shields.io/badge/DOI-10.1063%2F1.4991798-blue)](https://doi.org/10.1063/1.4991798)

This is the official repository of the `xtb-IFF` program developed by the Grimme group in Bonn.


## Installation

Statically linked binaries can be found at the [latest release page](https://github.com/grimme-lab/xtbiff/releases/tag/latest).
To extract the binaries, use the following command.

```bash
tar -xf xtbiff.tar.xz
```

After extracting the file, the `xtbiff` program is directly usable.

If it should be used with the QCG algorithm implemented in [`CREST`](https://github.com/grimme-lab/crest), make sure to source it correctly by adding it to the *PATH* variable. This was successful when the following command displays the path of `xtb-IFF`. 

```bash
which xtbiff
```

## Use as a Stand-Alone Program

For using the `xtbiff` as a stand-alone program, two LMO files have to be previously generated with the [`xtb`](https://github.com/grimme-lab/xtb) program. This can be done by providing the `--lmo` flag when exectuing `xtb`. A list of further options is displayed by executing the program. This can be done without any input.


## Citations

1. S. Grimme, C. Bannwarth, E. Caldeweyher, J. Pisarek, A. Hansen, *J. Chem. Phys.*, **2017**, 147, 161708.
  DOI: [10.1039/C9CP06869D](https://doi.org/10.1063/1.4991798)
