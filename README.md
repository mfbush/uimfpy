# uimfpy
A python library for UIMF files

# Requirements
LZF package: https://github.com/teepark/python-lzf

# How to install
First, ensure that Visual C++ 14.0 or new is installed on your computer. The python-lzf package requires it. 

Then, install the python-lzf package listed above with the following command:

 ```python
 pip install git+https://github.com/teepark/python-lzf.git
 ```
Next, install the uimfpy using the same command.

```python
pip install git+https://github.com/bzercher/uimfpy.git
```

# How to use
```python
reader = UIMFReader('test/test.uimf')
```
* Please refer to the unittest in [test](test/TestUIMFReader.py). 
