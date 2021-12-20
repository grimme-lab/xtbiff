# xtbiff

[![Latest Version](https://img.shields.io/github/v/release/grimme-lab/crest)](https://github.com/grimme-lab/xtbiff/releases/tag/latest)
[![DOI](https://img.shields.io/badge/DOI-10.1063%2F1.4991798-blue)](https://doi.org/10.1063/1.4991798)

This is the official repository of the `xtb-IFF` program developed by the Grimme group in Bonn.


## Installation

Statically linked binaries can be found at the [latest release page](https://github.com/grimme-lab/xtbiff/releases/tag/latest).
To extract the binaries, use the following command.

```bash
tar -xf xtbiff.tar.xz
```

After downloading and extracting the file, it is directly usable.

If the `xtb-IFF` should be used with the QCG algorithm implemented in [`CREST`](https://github.com/grimme-lab/crest), make sure to source it correctly by adding it to the *PATH* variable. This is the case when the following command displays the path of `xtb-IFF`. 

```bash
which xtbiff
```

## Usage

For using the `xtb-IFF` as a stand-alone program, a list of commands is displayed by typing `xtbiff`. In general, two LMO files have to be previously generated with `xtb` by providing the `--lmo` flag. These are then used as input.


## Citations

1. S. Grimme, C. Bannwarth, E. Caldeweyher, J. Pisarek, A. Hansen, *J. Chem. Phys.*, **2017**, 147, 161708.
  DOI: [10.1039/C9CP06869D](https://doi.org/10.1063/1.4991798)
