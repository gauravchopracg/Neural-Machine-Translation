Neural-Machine-Translation
===
The aim of this repository is to illustrate how to create and train a neural network for sequence to sequence language translation (seq2seq) for sentences and phrases from English to Hindi.

The process of building our neural machine translation end-2-end pipeline will be as follows:
  * Pre-process our data (Data Preprocessing)
    * Convert to lowercase
    * Remove all the special characters
    * Remove all the numbers from text
  * Tokenization
    * Sentence tokenization
    * Remove extra spaces (leading and trailing)
    * START and END tokens to sentence
  * Model Architecture
    * Choose an sequence model
    * Architecture and layers explanation
    * Attention and explanation
  * Model training and Hyperparameters Optimization
    * Epochs, Batch Size, Layers
    * Sample sentence prediction
    
## Dependencies

* numpy (http://www.numpy.org/)
* functools
* PIL (http://stackoverflow.com/questions/20060096/installing-pil-with-pip)
* tensorflow (https://www.tensorflow.org/versions/r0.10/get_started/os_setup.html#pip-installation)
* matplotlib (http://matplotlib.org/1.5.1/users/installing.html)
* urllib (https://pypi.python.org/pypi/urllib3)
* os
* zipfile

Install missing dependencies using [pip](https://pip.pypa.io/en/stable/installing/)

## Usage

Once you have your dependencies installed via pip, run the demo script in terminal via

```
jupyter notebook
```
or simply try [colab version](https://colab.research.google.com/drive/1q0fkEHdqco-4mXAUy9GMp8fgxRKErvLi?usp=sharing)
