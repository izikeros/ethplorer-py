<p>
<a href="https://github.com/psf/black"><img alt="Code style: black" src="https://img.shields.io/badge/code%20style-black-000000.svg"></a>
</p>

# ethplorer-py
Simple ethplorer.io API for python

## Install
In the project's base directory just run:
```sh
python setup.py install
```

or install with pip:
```sh
pip install git+https://github.com/izikeros/ethplorer-py.git
```
you can add `git+https://github.com/izikeros/ethplorer-py.git` to your requirements.txt file

## Usage
```python
from ethplorer.address import Address

call = Address(address="0x48c80f1f4d53d5951e5d5438b54cba84f29f32a5")
print(call.get_address_info())
print(call.get_address_history())
print(call.get_address_transactions())
```

## Credits
Original author: [guillelo11](https://github.com/guillelo11)
