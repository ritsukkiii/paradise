# paradise
Implementation of the "PARADISE: Exploiting Parallel Data for Multilingual Sequence-to-Sequence Pretraining" by Reid and Artexte

## Steps to run for testing (for en-hi denoising):
1. Download the files that are in this repo containing preprocessed data
  - the unprocessed datafiles are in ./Datasets
  - files created after spm.encode are in ./en-hi/encode
  - files created after fairseq preprocess are in ./en-hi/preprocess
2. run the command with the specified arguments in test_en-hi.sh
  - checkpoints will be saved to ./en-hi/checkpoints
