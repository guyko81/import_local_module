# Generate module from local file
A Python package to dynamically create module from local or remote Python file.

# Install
```
pip install modgen
```
# Usage
```
import modgen
my_selected_module_name = modgen.create('my_selected_module_name', 'path/to/my/module/file.py')
# or 
# my_selected_module_name = modgen.create('my_selected_module_name', 'https://path/to/my/module/file.py')
```
