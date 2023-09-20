# ft_package

The `ft_package` is a simple testing example to understand the basics of developing a Python package.

## Installing the package
Before installing the package make sure you have `pip` installed.

Run `pip install ./dist/ft_package-0.0.1.tar.gz`

or `pip install ./dist/ft_package-0.0.1-py3-none-any.whl`

to install the package.

Now you are ready to use the package!


## Example for Package Usage

```
from ft_package import count_in_list

print(count_in_list(["toto", "tata", "toto"], "toto")) # output: 2
print(count_in_list(["toto", "tata", "toto"], "tutu")) # output: 0
```

```
from ft_package import greetings

greeting.greet_friend('Blue')
greeting.greet_world()
greeting.greet_people()
greeting.greet_42()
```
