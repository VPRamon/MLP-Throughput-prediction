# MLP Throughput prediction

## Installation

Make sure you have installed the PyTorch library: https://pytorch.org/get-started/locally/
```bash
conda install pytorch torchvision torchaudio cudatoolkit=10.2 -c pytorch
```
or
```bash
pip install torch===1.7.0 torchvision===0.8.1 torchaudio===0.7.0 -f https://download.pytorch.org/whl/torch_stable.html
```


## Dataset
The dataset used during the project can be downloaded in the following link:
https://zenodo.org/record/4106127#.Ykxw3PexXmg

## Usage

### Properly set the input data directory
```python
from google.colab import drive                             ## Comment if executing in local machine

# This will prompt for authorization.                     
drive.mount('/content/drive')                              ## Comment if executing in local machine

data_path = '/content/drive/My Drive/Data/...'             ## Path to where data is stored
results_path = '/content/drive/My Drive/Results/...'       ## Path where results will be stored
input_train = data_path+'Train/input_node_files/'
output_train_sim = data_path+'Train/output_simulator/'
input_test = data_path+'Test/input_node_files_test/'
output_test_sim = data_path+'Test/output_simulator_test/'
```

### It may take some time to load the whole dataset, be patient

contact email: vallespuigramon@gmail.com
