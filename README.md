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
