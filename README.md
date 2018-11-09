# Twitter Bot Sample
A sample Twitter bot in Python - created by [@ykdojo](https://github.com/ykdojo). This is part of the [Edit Dojo](https://github.com/ykdojo/editdojo) project.

---

## Set up notes

### How to install Tweepy

First, check your Python version with ``python3 --version`` or ``python --version`` on console (terminal/shell/command prompt).

#### If you don't have Python 3 installed (if the above command fails):

Either install Python 3 on your computer OR use something like PythonAnywhere (https://csdojo.io/py).

#### If you have Python 3.6, you can just run:

``pip3 install tweepy``

#### If you have Python 3.7, run the following instead:

``pip3 install -U git+https://github.com/tweepy/tweepy.git@2efe385fc69385b57733f747ee62e6be12a1338b``

If the above command doesn't work, try replacing ``pip3`` with ``pip`` also.

#### If you have Python 3.7 and want to use pipenv, use:

``pipenv install -e git+https://github.com/tweepy/tweepy.git@2efe385fc69385b57733f747ee62e6be12a1338b#egg=tweepy``

