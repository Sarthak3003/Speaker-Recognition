### File structure

* `myconfig.py`: all the configurations of this library
* `dataset.py`: code for parsing datasets
* `feature_extraction.py`: code for extracting acoustic features with librosa
* `specaug.py`: code for SpecAugment
* `neural_net.py`: code for building neural networks and training with PyTorch
* `evaluation.py`: code for inference and evaluation
* `generate_csv.py`: a utility script to generate a CSV file to represent a dataset
* `tests.py`: unit tests

### Download data

Download LibriSpeech datasets from OpenSLR website

### Update configurations

Configurations are in `myconfig.py`.

You have to update `TRAIN_DATA_DIR` and `TEST_DATA_DIR` path to where your LibriSpeech train and test datasets are located.