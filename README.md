# python_virtualenv
python virtual environment with multiplate python version

# Steps:
## Install multiple versions of Python into machine:
```
  Example:
    1. python27
    2. python36
    3. python39
    4. python310
    5. python311
```
## Set Python Path into Windows System Variables:

## Create A Project-Root-Folder for Python project.
```
  cmd:\> mkdir virtual-env-poc
  cmd:\> cd virtual-env-poc
```

## Create Virtual Environment:
```
 cmd: virtual-env-poc\> python -m virtualenv -p C:\Python\Python27\python.exe myVirtualEnv27
 cmd: virtual-env-poc\> python -m virtualenv -p C:\Python\Python310\python.exe myVirtualEnv310
 cmd: virtual-env-poc\> python -m virtualenv -p C:\Python\Python311\python.exe myVirtualEnv311

```

## Activate Virtual Environment:
```
 cmd: virtual-env-poc\> .\myVirtualEnv27\Scripts\activate
--or--
 cmd: virtual-env-poc\> .\myVirtualEnv310\Scripts\activate
--or--
 cmd: virtual-env-poc\> .\myVirtualEnv311\Scripts\activate
```

## Install dependencies either manually or using requirement.txt
```
 (myVirtualEnv27) cmd: virtual-env-poc\> python -m pip install numpy

```
## de-activate Virtual Environment:
```
 (myVirtualEnv27) cmd: virtual-env-poc\> deactivate
 cmd: virtual-env-poc\>
```

# References:
https://www.youtube.com/watch?v=sk-ikK90AyQ
