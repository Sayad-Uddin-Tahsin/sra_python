# sra-python

`sra-python` is a Python wrapper for the [some-random-api](https://some-random-api.ml) REST API.

```python
import sra

>>> print(sra.animal.Panda.image_link)  # Prints a Panda Image link
"https://i.imgur.com/YVLrUO9.jpg"
>>> print(sra.animal.Panda.fact)  # Prints a Panda Fact
"Giant pandas have been driven out of the lowland areas where they used to live and now are found only in the Chinese provinces of Sichuan, Gansu, and Shaanxi. The forests in these provinces are very damp and rainy. In one year, a forest may receive up to 50 inches of rain and snow."
>>> sra.animal.Panda.save_image()  # Saves the Image
```
With `sra-python`, you can easily access the various endpoints of `some-random-api` in your Python projects, making it a powerful tool for working with image, fact, and other types of data.

[![Status](https://img.shields.io/static/v1?label=Status&message=Stable&color=green)](https://pypi.org/projects/sra-python) [![Supported Versions](https://img.shields.io/badge/3.7%20%7C%203.8%20%7C%203.9%20%7C%203.10%20%7C%203.11-3670A0?style=flat&logo=python&logoColor=ffdd54&label=Python)](https://pypi.org/projects/sra-python)

## Installation
You can install `sra-python` using `pip`:
```console
python -m pip install sra-python
```
`sra-python` requires Python 3.7 or later.

## Endpoints
`sra-python` is currently under development. Currently, only the `animal` and `animu` categories of APIs are available in stable version, but we're working to add more.

## Cloning the Repository
If you want to work with the development version of sra-python, you can clone the repository and install it using pip:
```console
pip install git+https://github.com/Sayad-Uddin-Tahsin/sra-python.git
```
This will install the package from the cloned repository.
