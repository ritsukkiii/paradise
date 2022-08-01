# paradise
Implementation of the "PARADISE: Exploiting Parallel Data for Multilingual Sequence-to-Sequence Pretraining" by Reid and Artexte

## Steps to run for testing (for en-hi denoising):

1. get the mbart50.pretrained files from googledrive/models and unzip
2. download the en-hi files
  - files created after spm.encode are in ./en-hi/encode
  - files created after fairseq preprocess are in ./en-hi/preprocess
3. run the command with the specified arguments in test_pycharm.txt
  - checkpoints will be saved to ./en-hi/checkpoints
