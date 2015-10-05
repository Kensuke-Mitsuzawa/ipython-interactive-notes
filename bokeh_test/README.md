# setting up

## pyenv and anaconda 

it's best to install all in anaconda distribution.

And I recommend to use `pyenv` to switch original-python/anaconda-python

To setup pyenv environment, see [here](https://github.com/yyuu/pyenv)

To install anaconda, put following command

```
[sudo] pyenv install anaconda-2.1.0
```

You can switch anaconda environment super easily

```
pyenv global anaconda-2.1.0
```

## Bokeh

It's easy to setup Bokeh if you are already to use anaconda.

See [this document](http://bokeh.pydata.org/en/latest/docs/installation.html)

## start ipython notebook

when you ready to call Bokeh, type following command

```
ipython notebook
```

This command lunchs ipython in local server and provides GUI interactive interface to you.
