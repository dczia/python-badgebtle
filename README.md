# DEF CON badge bluetooth libary

A library based on bluepy that performs bluetooth scan for DEF CON badges.

## Usage

#### Basic
```
from badgebtle import BadgeBTLE
b = BadgeBTLE()
neighbors = b.scan()
print(neighbors)
```

## Development

#### Setup
```
$ git clone https://github.com/dczia/python-badgebtle.git
$ virtualenv-3 v
$ source ./v/bin/activate
$ pip install -r requirements.txt
```

#### Build and upload to PyPi repository
```
$ python setup.py sdist bdist_wheel
$ pip install twine
$ twine upload dist/badgebtle-x.x.x* #<-- Requires credentials.
```
