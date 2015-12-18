# Pyncd
A Python powered normalized compression distance (NCD) calculator.

All data are created equal but some data are more alike than others. The NCD uses a method expressing this alikeness
using a similarity metric based on compression. The NCD is a non-negative number 0 ≤ r ≤ 1 representing how different the two files are. Smaller numbers represent more similar files. It is parameter-free in that it doesn’t use any features or background knowledge about the data, and can without changes be applied to different areas and across area boundaries.

#### References
* Rudi Cilibrasi and Paul M. B. Vitányi. Clustering by compression. *IEEE Transactions on Information Theory*, 51:1523–1545, 2005
