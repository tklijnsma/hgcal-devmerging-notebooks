# Setup

Basic environment setup:

```
conda create -n hgcal-devmerging python=3
conda activate hgcal-devmerging

git clone git@github.com:tklijnsma/devhgcaltruth.git # or the https equivalent
pip install -e devhgcaltruth/

pip install notebook
pip install plotly
```

Get the notebooks here:

```
git clone https://github.com/tklijnsma/hgcal-devmerging-notebooks.git
cd hgcal-devmerging-notebooks
```

Download some example rootfiles to get started:

```
wget https://cernbox.cern.ch/index.php/s/lYNghQUwb4htXhL/download -O hgcalntups.tar
mkdir ntups
tar xvf hgcalntups.tar -C ntups/
rm hgcalntups.tar
```
