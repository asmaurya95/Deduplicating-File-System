# Deduplicating File System

## Description
The aim of this project is to implement a simple filesystem using [fusepy](https://pypi.org/project/fusepy/), a Python module that provides a simple interface to [FUSE](http://fuse.sourceforge.net/). Furthurmore, use block-level [data deduplication](https://en.wikipedia.org/wiki/Data_deduplication) to improve storage utilization.

## Requirements

- Python 2.x (2.6 or later)
- fusepy

## Instructions

##### Method 1  

- Make the script executable 
```
$ chmod +x dfs.py
```
- Run the script
```
$ ./dfs.py <root directory> <mount directory>
```
##### Method 2

- Run script by calling the python interpreter
```
$ python dfs.py <root directory> <mount directory>
```
