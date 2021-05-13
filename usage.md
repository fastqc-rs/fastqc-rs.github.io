## Usage

```
fqc -q path/to/my_sequence.fastq > report.html
```

Arguments:

| Parameter                 | Default       | Description   |	
| :------------------------ |:-------------:| :-------------|
| -q --fastq 	       |	-           |The path to the FASTQ file to use
| -k          | 5           |The length k of k-mers for k-mer counting
| -s --summary          | -           |Creates an output file for usage with [MultiQC](https://multiqc.info) under the given path
