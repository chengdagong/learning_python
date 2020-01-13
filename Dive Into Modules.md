### Relative imports

According to [PEP0328](https://www.python.org/dev/peps/pep-0328/):

> Relative imports use a module's \_\_name\_\_ attribute to determine that module's position in the package hierarchy. If the module's name does not contain any package information (e.g. it is set to '__main__') then relative imports are resolved as if the module were a top level module, regardless of where the module is actually located on the file system.

It's import to note that relative imports are based on the \_\_name\_\_ attribute of the module, when the module is loaded. It's absolutely irrelevant where the file is actually located on the file system.

