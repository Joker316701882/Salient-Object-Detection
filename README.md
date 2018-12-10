# Salient-Object-Detection
This is tensorflow implementation for cvpr2017 paper "Deeply Supervised Salient Object Detection with Short Connections"

<h3>Pretrained Model</h3>
https://drive.google.com/open?id=0B6l9O8aWij8fUGtVNldUTXA4eHc

<h3>Usage</h3>
1. Download pretrained model and put them under folder "salience_model" ,(need to create folder yourself)<br />
2. run code<br />

If you want to test whole folder images, run this:  

```
python inference.py --rgb_folder=[your folder]
```

sample:  

```
python inference.py --rgb_folder=./test
```

If you want to test only one image,run this:  

```
python inference.py --rgb=[your image]
```

sample:

```
python inference.py --rgb=animal1.jpg
```

<h3>Sample</h3>

![Sample](samples/1.png)

more detail please read source code.


### 2018-03-02

I'm considering to open source training code recently(in several months), but to be honest, I don't understand why this model works so well(even there is some mis-using of tensorflow, but it works..). 
# LICENSE
MIT License

Copyright (c) 2018 Ge Zheng

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

