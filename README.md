# Pyncd
A Python powered normalized compression distance (NCD) calculator.

All data are created equal but some data are more alike than others. The NCD uses a method expressing this alikeness
using a similarity metric based on compression. The NCD is a non-negative number 0 ≤ r ≤ 1 representing how different the two files are. Smaller numbers represent more similar files. It is parameter-free in that it doesn’t use any features or background knowledge about the data, and can without changes be applied to different areas and across area boundaries.

## Usage
```
git clone git@github.com:alephmelo/pyncd.git
python pyncd.py
```

Change the names of the files to the names you want to check the distance.
``` python
x = open('1.png', 'rb').read() # file 1 of any type
y = open('2.png', 'rb').read() # file 2 with same type as file 1
```

#### References
* Rudi Cilibrasi and Paul M. B. Vitányi. Clustering by compression. *IEEE Transactions on Information Theory*, 51:1523–1545, 2005
