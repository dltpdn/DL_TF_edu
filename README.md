# DL_TF_edu
Welcome to Deep Learing with Tensorflow basic course.

## Google Colab
* https://colab.research.google.com
* uploading file to colab virtual machine
```python
from google.colab import files
uploaded = files.upload()
for fn in uploaded.keys():
  print('User uploaded file "{name}" with length {length} bytes'.format(
      name=fn, length=len(uploaded[fn])))
```
