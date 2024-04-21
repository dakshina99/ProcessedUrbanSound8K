# ProcessedUrbanSound8K

1. Set sample rate of all the wav files to 20kHz
2. All the clips set to 100k samples by padding and croping clips
3. Merge all the 10 folds and prepare 5 stratified folds and get a NPZ file as the resultant dataset
4. Classes are 0 indexed

## Instructions

1. create a folder named "data" and include the 10 folds into that
2. you can change the sample rate and the number of samples accordingly
3. create a python env, install the requiered libraries and run the notebook "preprocess.ipynb"
4. NPZ file will be saved in the data folder