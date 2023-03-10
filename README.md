# logmaster
allows you to log things easier with color

# needed packages
- Colorama

# code examples
```from logmaster import info

infoobj = info()

infoobj.log("tst")```

### adding custom objects
```from logmaster import info
from colorama import Fore as Color

infoobj = info(cus_braket=Color.CYAN, cus_info=Color.CYAN, cus_text=Color.CYAN) # this is all the custom color abilities

infoobj.log("tst")``` 
OUTPUT = [INFO]  tst
