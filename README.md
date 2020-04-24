# driving-dirty
DL Project 2020

# How to run
First, install dependencies

```python
# clone project   
git clone https://github.com/annikabrundyn/driving-dirty

# install project   
cd driving-dirty
pip install -e .   
pip install -r requirements.txt
```
# Training the Autoencoder

```python
python src/autoencoder/autoencoder.py --link '/scratch/ab8690/DLSP20Dataset/data' --gpus 1 --max_epochs 5 --batch_size 32
```
