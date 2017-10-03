# Jupyter Notebooks for Deep Learning Course

Forked from the repository containing jupyter notebooks for the book [Deep Learning with Python (Manning Publications)](https://www.manning.com/books/deep-learning-with-python?a_aid=keras&a_bid=76564dff)

## Prerequisites

- Install Python 3.6
- Install requirements with ```pip install -r requirements.txt```
- Install PyCairo:

```shell
git clone https://github.com/pygobject/pycairo.git
cd pycairo
python setup.py install
```

## Data 

### Kaggle Cats and Dogs

- Download the preprocessed Kaggle Cats and Dogs dataset from [this link](https://drive.google.com/file/d/0B_ebsCRJm2BfclJOblQ3UWZkeGs/view?usp=sharing)
- Extract it under the ```data/``` directory. After extraction you should have the following structure:

```shell
data/
data/cats_and_dogs_small/train
data/cats_and_dogs_small/validation
data/cats_and_dogs_small/test
```

### UCF-101 (Coming soon)
- Download pre-extracted features [here]() (16GB).
- Extract them under ```data```:
```shell
data/
data/ucf101/train...
```

### Models (Coming soon)

- The pretrained models and additional files that were provided for these sessions can be downloaded from [this]() link. Download, extract, and place under ```data```.

```shell
data/
data/models/
data/models/model_name.pkl
...
```