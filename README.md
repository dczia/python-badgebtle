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
