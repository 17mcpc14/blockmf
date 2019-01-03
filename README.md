# Block Matrix Factorization 

Block based matrix factorization approach that splits a given matrix into required number of blocks and factorization achieved on individual blocks

Refer: https://arxiv.org/pdf/1901.00444.pdf for theorical basis.

## Getting Started


### Prerequisites

```
Python 3.0

The CPU based Block matrix factorization has been developed using python using python.

```

### Installing

```
git clone 'https://github.com/17mcpc14/blockmf'

```

## Running the tests

Below MF implmentations are hardcoded to run on data/R.txt - a randomly generated dataset of 1000x1000 dimension with values ranging from 0 - 30. 

```
1. src/cpumf.py - CPU based MF implementation with SGD convergence
2. src/blockcpumf.py - CPU based BMF implementation with SGD converegence
3. src/blockparallelcpumf.py - CPU based BMF with parallel/multi-threaded implementation with SGD convergence
```

Note: the programs can be simply modified from R.txt to any other dataset. 

## Authors

* **Prasad G Bhavana** - *Initial work* - [LinkedIn](https://www.linkedin.com/in/prasadbhavana/)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Vineet C Nair, Professor, University of Hyderabad
* Bilsangeeth D, M Tech Student, University of Hyderabad
