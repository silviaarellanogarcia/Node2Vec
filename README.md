# Node2Vec
This repository aims to reproduce the Node2Vec method as originally presented in the paper titled "node2vec: Scalable Feature Learning for Networks" by Grover and Leskovec.

## Files Overview:

### 1. node2vec.ipynb:
   - Designed for datasets loaded in .csv files.
   - Contains the primary implementation of the Node2Vec method, producing a 128-dimensional embedding with Graph information.
   - Includes an evaluation using Node Classification.

### 2. node2vec_PPI.ipynb:
   - Tailored for datasets from the PyTorch Geometric library.
   - Adapts the content of the previous file for compatibility with these datasets.

**Reference:**
Grover, A., & Leskovec, J. (2016). node2vec: Scalable Feature Learning for Networks. Proceedings of the 22nd ACM SIGKDD International Conference on Knowledge Discovery and Data Mining, 855–864. [https://doi.org/10.1145/2939672.2939754]
