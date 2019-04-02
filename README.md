# Python2-to-Python3
When deploying a big project, or more explicitly, deploying an 'ancient' project, pythoners may come across a version collision with IDE.This repository provides a convenient way for transfering python2 scripts to python3.  
  
So just give the target folder like:
```python
  localfolder = 'PaddlePaddle-master'
```
Or it can be an absolute path.  
And run this script, you will get the refractoring infomation in console. For you are excuting "2to3 -n -w [filename]" actually.  

The requirement for this project is to have py2to3 installed.  
```bash
  pip install 2to3
```
"2to3" means to transform python2 to python3 scripts.
  
Last but not the least, this works out for windows platform only!!!
