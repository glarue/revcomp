### Dependencies

This script needs the [biogl](https://github.com/glarue/biogl) module to function properly. If you use (or can get) `pip`, you can simply do

```python3 -m pip install biogl```

to add the package to a location reachable by your Python installation. 

Otherwise, you can clone the `biogl` repo and source it locally (to run from anywhere, you'll need to add it to your PYTHONPATH environment variable, a process that varies by OS):

```git clone https://github.com/glarue/biogl.git```

### Usage info

```
usage: revcomp [-h] [-f FILE] [--no_mask] [--no_lower] [seq]

reverse-complement a nucleotide sequence

positional arguments:
  seq                   nucleotide sequence to be reverse-complemented
                        (default: None)

optional arguments:
  -h, --help            show this help message and exit
  -f FILE, --file FILE  file to reverse-complement (FASTA-compatible)
                        (default: None)
  --no_mask             don't mask non-ACTG characters with N (default: False)
  --no_lower            consider lowercase input invalid (will still reverse)
                        (default: False)
```
