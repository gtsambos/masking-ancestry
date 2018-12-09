# masking-ancestry

This repository will contain scripts that can be used to obtain ancestry-masked `.bed` files for the NCIG project. It will be inspired by/possibly partly copied off Alicia Martin's `ancestry_pipeline` code [here](https://github.com/armartin/ancestry_pipeline).

Two inputs are needed:

#### 1. vcf file
This will contain the genotype information of samples.

#### 2. Local ancestry output from RFMix
These contain the results of the local ancestry inference on these samples. 

At this stage, it's particularly important that the number of populations is the same as the number of populations we will be using in the 'real' runs. 

There should be one file with suffix `*.ForwardBackward.txt` containing lots of floating point numbers, and another file with suffix `*.Viterbi.txt` containing integers. 


### Access

This repository will soon be made private. Once this happens, users will need my permission to view/download these scripts. Please make a GitHub account if you don't already have one, and send me your account details so I can arrange this.