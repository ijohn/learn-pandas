# Learning pandas

This repository contains a couple of [Jupyter Notebook](https://jupyter.org) files I created while I was learning [pandas](https://pandas.pydata.org).

If you want to learn from these files and you have [Docker](https://www.docker.com/) installed, you only need to do the following:

```
$ git clone https://github.com/ijohn/learn-pandas.git
$ cd learn-pandas
$ docker run --rm -p 8888:8888 -v "${PWD}":/home/jovyan/work jupyter/scipy-notebook
```

After that, read the console output which will tell you the complete URL (local) where you could see the notebooks with your web browser. New notebooks will be saved to the working directory.

Have fun!
