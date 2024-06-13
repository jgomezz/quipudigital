
### Build and Upload Your Package

First, install twine and wheel which you will use to build and upload the package:

```
pip install twine wheel
```

Then, run the following commands in your terminal:

```
python setup.py sdist bdist_wheel
twine upload dist/*
```