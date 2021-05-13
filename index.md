# fastqc-rs

![Rust](https://github.com/fxwiegand/fastqc-rs/workflows/Rust/badge.svg)
[![Crates.io](https://img.shields.io/crates/d/fastqc-rs.svg?label=crates.io%20downloads)](https://crates.io/crates/fastqc-rs)
[![Crates.io](https://img.shields.io/crates/v/fastqc-rs.svg)](https://crates.io/crates/fastqc-rs)
[![Crates.io](https://img.shields.io/crates/l/fastqc-rs.svg)](https://crates.io/crates/fastqc-rs)
[![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/fastqc-rs/README.html)
[![Bioconda downloads](https://img.shields.io/conda/dn/bioconda/fastqc-rs?label=bioconda%20downloads)](https://anaconda.org/bioconda/fastqc-rs)

A fast quality control tool for FASTQ files written in rust inspired by [fastQC](https://www.bioinformatics.babraham.ac.uk/projects/fastqc/). Results are written to `stdout` as a self containing html report with visualizations for all statistics. Summary files for usage with [MultiQC](https://multiqc.info) can also be generated.

Available statistics are:
- Read length
- Sequence quality score
- Sequence quality per base
- Sequence content per base
- k-mer content
- GC content

For a detailed list of changes, take a look at the [CHANGELOG](https://github.com/fastqc-rs/fastqc-rs/blob/main/CHANGELOG.md).
