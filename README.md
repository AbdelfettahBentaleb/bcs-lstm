# BCS Computational Tutorial: LSTM Sentiment Classifier

## LSTM's for Sequence Modeling
Lab can be found at `Lab.ipynb`.

## Running the labs
The labs are jupyter notebooks, so run `jupyter notebook` in this directory, and then click on the proper file name in jupyter to open it.

## Install Instructions
Please copy the following commands to your bash terminal:

## Pip Instructions
If you are using pip:
```
git clone https://github.com/yala/introdeeplearning;
cd introdeeplearning;
pip install virtualenv;
virtualenv intro_dl;
source intro_dl/bin/activate;
pip install --upgrade pip;
pip install tensorflow;
pip install matplotlib;
pip install pandas;
pip install jupyter;
python -m ipykernel install --user --name=intro_dl
echo 'done';
jupyter notebook
```
From within jupyter, in the top-right corner, select the kernel named "intro_dl". This is the kernel that will have the contents of your virtualenv.

## Conda Instructions
```
git clone https://github.com/yala/introdeeplearning;
cd introdeeplearning;
conda create -n intro_dl;
source activate intro_dl;
conda install -c conda-forge tensorflow;
pip install matplotlib;
pip install pandas;
conda install jupyter;
echo 'done';
jupyter notebook
```


### If you don't have git
- Just click "Clone or Download Button" and then click 'Download Zip' on this page: [https://github.com/yala/introdeeplearning](https://github.com/yala/introdeeplearning)

