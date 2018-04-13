# namegen
A python module by Greg Wojtak

## Overview
This is a simple, stupid, potentially entertaining, yet highly useful (in my
opinion) port of the container name generation code from the Docker project.
It is extremely straight-forward and could be easily modified with your 
own adjectives and names.

## Usage
Just copy the ```namegen``` directory into somewhere in your python search
path.  Import it in your script and run the ```namegen()``` function.

```python
import namegen

name_label = namegen.namegen()
print(name_label)
```
This would generate something like:
```bash
[gwojtak@elementaryos]$ ./test.py
abbreviated_vaughn
```

## Contributions
If you feel compelled to contribute, feel free to:
1. Fork it
1. Make your changes
1. Create a branch
1. Commit your changes
1. Push your changes
1. Submit a Pull Request
1. ???
1. Profit.
