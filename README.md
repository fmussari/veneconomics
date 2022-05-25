# veneconomics
> I don't know if this is a library or a series of scripts to gather sconomic data relevant to Venezuela.


This file will become your README and also the index of your documentation.

## Install

`pip install your_project_name`

## How to use

Inside each module folder, like for example `veneconomics`, there is a `__init__.py` file.
According to this video: [nbdev tutorial](https://youtu.be/Hrs7iEYmRmg), adding to that file the following line of code:
```
from .first_model import *
```  
Will allow to load the module like this:

```python
from veneconomics import *
```

But in my case it caused problems and works leaving `__init__.py` file as is.
Well, not really since it didn't pass github actions on commit.  
So I don't know what is best, if leave it origianl to locally execute `nbdev_build_docs` vs commit. I think it is best to pass the commit.

Say Hello

```python
say_hello("Ale")
```




    'Hello Ale!'


