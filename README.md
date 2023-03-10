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

***ALWAYS GO TO THE LATEST VER TO PREVENT BUGS***
*if you use v1 code in v2 it will warn you in some cases*

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
~Coming Soon~
Its here! The examples may look the same but there are some general fixes.

**Basic Info Logging**
```python
from logmaster import Info # make sure to use Info and not info

infoobj = Info()

infoobj.log("tst")
```

**Basic WARN Logging**
```python
from logmaster import Warn

warnobj = Warn()

wobj.log(alert="This is a warn!!!")
```

### Custom Color Objects
***TO DO THIS AND PREVENT ERRORS USE COLORAMA***

**Warn vvvv**
```python
from logmaster import Warn
from colorama import Fore as Color

wobj = Warn(cus_braket=Color.CYAN, cus_wWarnarn=Color.CYAN, cus_text=Color.CYAN) # this is all the custom color abilities

wobj.log("tst")
```

**Info vvvv**
```python
from logmaster import Info
from colorama import Fore as Color

infoobj = Info(cus_braket=Color.CYAN, cus_info=Color.CYAN, cus_text=Color.CYAN) # this is all the custom color abilities

infoobj.log("tst")
```
***RETURNPRINT IS THE SAME AS V1 DOCUMENTATION***
