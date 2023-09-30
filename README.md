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

## De-activate Virtual Environment:
```
 (myVirtualEnv27) cmd: virtual-env-poc\> deactivate
 cmd: virtual-env-poc\>
```

## Create requirment.txt:
```
 (myVirtualEnv27) cmd: virtual-env-poc\> python -m pip freeze > requirements.txt

```

## Install dependencies manually or using requirment.txt:
```
 (myVirtualEnv27) cmd: virtual-env-poc\> python -m pip install numpy
--or--
 (myVirtualEnv27) cmd: virtual-env-poc\> python -m pip install -r .\requirements.txt
```

## Check installed dependencies:
```
 (myVirtualEnv27) cmd: virtual-env-poc\> python -m pip list
```

# References:
[![SC2 Video](https://img.youtube.com/vi/sk-ikK90AyQ/0.jpg)](https://www.youtube.com/watch?v=sk-ikK90AyQ)

[![SC2 Video](https://img.youtube.com/vi/ggRsauJcEyE/0.jpg)](https://www.youtube.com/watch?v=ggRsauJcEyE)

[![SC2 Video](https://img.youtube.com/vi/Lah7WGW6exg/0.jpg)](https://www.youtube.com/watch?v=Lah7WGW6exg)

[![SC2 Video](https://img.youtube.com/vi/2P30W3TN4nI/0.jpg)](https://www.youtube.com/watch?v=2P30W3TN4nI)
