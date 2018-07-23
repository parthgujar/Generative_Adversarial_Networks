Overview
============
This is the Generative Adversarial Network Demo written in Python using the Theano ML library. There is a default static gaussian distribution curve that the generator curve continously tries to mimic. Each timestep it gets better and better as it slowly gets better at fooling the disciminator network. Here's a cool live [demo](http://cs.stanford.edu/people/karpathy/gan/)

![http://i.imgur.com/5qzjtgd.png](http://i.imgur.com/5qzjtgd.png)

Dependencies
============

* Python 2.7+ - (https://www.python.org/downloads/)
* matplotlib - `pip install matplotlib`
* theano - `pip install theano`
* scipy - `pip install scipy`
* foxhound (included)

Use [pip](https://pypi.python.org/pypi/pip) to install any missing dependencies

Basic Usage
===========
If your dependencies are installed you can just run the code! A pyplot GUI should pop up and it will get better and better as it trains. 

```shell
python demo.py
```

*Pull Requests are encouraged!!! This pyplot stuff can get wonky, so definitely make a PR if you see something that needs fixing.*


