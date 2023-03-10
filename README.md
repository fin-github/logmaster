# logmaster
allows you to log things easier with color

# needed packages
- Colorama

# Coming Soon
- [x] Warn

- [ ] Error

- [x] Nocolor (only on warn currently)

- [ ] File Logging

# code examples

## V1

```python
from logmaster import info

infoobj = info()

infoobj.log("tst")
```


### adding custom objects
```python
from logmaster import info
from colorama import Fore as Color

infoobj = info(cus_braket=Color.CYAN, cus_info=Color.CYAN, cus_text=Color.CYAN) # this is all the custom color abilities

infoobj.log("tst")
```

OUTPUT = [INFO]  tst
### returnPrint
adding returnPrint=True to infoobj.log() instead of printing ther output it will return the output.
if there are bad arguments for it, it will display this error:
```python
AttributeError: returnPrint has an invalid value of {returnPrint}
```

## V2
Coming Soon
