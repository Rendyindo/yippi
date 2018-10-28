<p align="center"><a href="https://e621.net/post/show/1411608"><img src="src/esix.png"></img></a></p>

# Yippi!  [![Documentation Status](https://readthedocs.org/projects/yippi/badge/?version=latest)](http://yippi.readthedocs.io/en/latest/?badge=latest) [![Build Status](https://travis-ci.org/Rendyindo/yippi.svg?branch=master)](https://travis-ci.org/Rendyindo/yippi)
Yippi is an e621 API wrapper for Python, to make everyone's life simplier.

# Requirements
+ Python 3.x
+ urllib
+ json

# Installation
Clone this repository, and type this down

```bash
$ pip install -e .
``` 

# Example
```python
results = yippi.search(['girly', 'male', 'fox']) # Searches e621 with "girly male fox" as query
results[0].file_url # Get the image/file's URL
``` 
[Full Documentation](https://yippidocs.rorre.me)