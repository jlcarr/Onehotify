# Onehotify

A Python script for converting categorical data into one-hot encoding

## Features
* Uses only standard Python libraries
* Takes input as either set or list format
* Uses only standard Python libraries
* Comes with a main contaning an illustrative example
* All functions have docstrings
* Simple design and usage.


## Installation
Requires Python 2.7
Simply add the file to the same directory you are working in and import it
```python
>>> import onehotify
```


## Usage
### Premade Example 
Running the script by itself in the terminal will output the following example

```console
$ python onehotify.py
The categories are: set(['orange', 'apple', 'banana'])

The encoding is
	0 maps to orange
	1 maps to apple
	2 maps to banana

The set ['apple', 'orange'] is encoded as
[1, 1, 0]
From which the original can be recovered by decoding
set(['orange', 'apple'])

```
