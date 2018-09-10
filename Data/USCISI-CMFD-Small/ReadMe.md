# USCISI-CMFD Dataset

### Introduction
This copy-move forgery detection(CMFD) dataset relies on
- [MIT SUN2012 Database](https://groups.csail.mit.edu/vision/SUN/)
- [MS COCO Dataset](http://cocodataset.org/#home)

More precisely, we synthesize a copy-move forgery sample using the following steps

1. select a sample in the two above dataset
2. select one of its object polygon
3. use both sample image and polgyon mask to synthesize a sample

More detailed description can be found in paper. 

### Folder Content
This USCISI-CMFD dataset folder contains the following things:

* **api.py** - USCISI-CMFD dataset API
* **data.mdb** - sample LMDB data file
* **samples.keys** - a file listing sample keys (each line is a key)
* **lock.mdb** - sample LMDB locker file
* **Demo.ipynb** - a python notebook show the usage of API
* **ReadMe.md** - this file


**NOTE** due to the repository size limit, the full USCISI-CMFD dataset will be provided upon request.