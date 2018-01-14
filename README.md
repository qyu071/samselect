# samselect
Solver for sample sequence selection from large DNA datasets for quorum planted motif search


# Source Code Usage
./my_sam [input file] [options]

[input file] the original data file
    
-l l: motif length
  
-d d: maximum number of mismatches between a motif and its instance
  
-q q: proportion of the input sequences containing motif instances

-T T: maximum number of sequences per sample sequence set (default 100)

-h: show this message.
