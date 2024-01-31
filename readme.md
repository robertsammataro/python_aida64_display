# python_aida64_display

This fork of the python_aida64 library intends to add a tkinter wrapper to allow for PC Hardware information to be displayed on the desktop allowing for transparent backgrounds which is not currently supported in vanilla Aida64

# python_aida64

A python implementation of reading aida64 data via shared memory. Works on Windows only, as you would imagine.

## Usage
```Python
>>> import python_aida64
>>> from pprint import pprint
>>> pprint(python_aida64.getData())
{'fan': [{'id': 'FCPU', 'label': 'CPU', 'value': '906'},
         {'id': 'FCHA1', 'label': 'Chassis #1', 'value': '2601'}],
 'pwr': [{'id': 'PCPUPKG', 'label': 'CPU Package', 'value': '19.13'},
 [... more lines]
```
