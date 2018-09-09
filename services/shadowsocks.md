# ShadowSocks

## 问题修复
### RuntimeError: can not find library crypto (DS platform)
```
Edit the file crypto/util.py (the path appears in the error message)

Comment out (with a #) the lines in function find_library like this:
#else:
# path = ctypes.util.find_library(name)
# if path:
# paths.append(path)
```
