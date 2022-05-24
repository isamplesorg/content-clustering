# content-clustering

Experimenting with clustering methods on different collections. 

(1) Initial experiments with 1% of data are in 'experiment with 1% of sample data'

(2) 2nd round of experiments with 100% of data for **each** sample collection are in their respective folder: SESAR, OPENCONTEXT, etc. Data are not pushed to the repo due to the size limit. Download data from https://mars.cyverse.org/data_dumps/GEOME.txt.zip [replace GEOME with other relevant collection name to get the data set). Download, unzip, and put the .txt file in the appropriate folder according to the jupyter file before executing the notebook (see also below to get cc.en.300.bin). 

(3) Terminology mining uses 100% source collection dataset. User can select the needed  fields from various source collections to mine term groups. 


**NOTE**: 
cc.en.300.bin used in the notebooks can be downloaded to your local with 

```
wget https://dl.fbaipublicfiles.com/fasttext/vectors-crawl/cc.en.300.bin.gz
```

If 'pip install fasttext' give you errors, the chance is that you need to first pip intall a fasttext whl that matches your python version. Find you matching whl file (e.g. fasttext-0.9.2-cp39-cp39-win_amd64.whl) from https://www.lfd.uci.edu/~gohlke/pythonlibs/#fasttext
