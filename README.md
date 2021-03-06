# Random Character Generator

## About the Package
The random character generator is a library used to generate strings with random letters/numbers

Current version: 0.0.5

## Installation

You can install this module using [PyPI](https://pypi.org)

`pip install randomcharactergenerator`

or 

`python3 -m pip install -U randomcharactergenerator`

## Usage

```python
# For a random string consisting of both numbers and alphabets
import randomcharactergenerator
string = randomcharactergenerator.rand_code()
print(string)
```

```python
# For a random string consisting of alphabets only
import randomcharactergenerator
string = randomcharactergenerator.alphabet_code()
print(string)
```

```python
# For a random string consisting of numbers only
import randomcharactergenerator
string = randomcharactergenerator.number_code()
print(string)
```

```python
# You can also choose to specify the number of characters
import randomcharactergenerator
string = randomcharactergenerator.rand_code(7)
print(string)

# Notes: Default number of characters is 5. 
# Warning: The 'characters' parameter must be an int only.
```

For more help, use the module_help() function

```python
import randomcharactergenerator
randomcharactergenerator.module_help()
```

## GitHub

https://github.com/SupremeCoder1707/randomcharactergenerator

## Credits

Author: HighlyIntelligentBeing
