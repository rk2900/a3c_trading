# A3C trading
Trading with recurrent actor-critic reinforcement learning

![Full_UML](supply_materials/Full_UML.png)

## Configuration: `config.py`
This file contains all the pathes and gloabal variables to be set up

## Dataset: download from [GDrive](https://drive.google.com/drive/folders/0B0ozwxwZOzYLM0F0V3ljRTFfd0U?usp=sharing)
After setting `config.py` please run this file to download and preprocess the data need for training and evaluation

## Environment: `trader_gym.py`
OpenAI.gym-like environment class

## Model: `A3C_class.py`
This file is containing `AC_network`, `Worker` and `Test_Worker` classes

## Training: `A3C_training.py`
Run this file, preferrable in `tmux`. During training it will create files in `tensorboard_dir` and in `model_dir`

## Testing: `A3C_testing.ipynb`
`Jupyter notebook` contains all for picturing
