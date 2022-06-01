# Marshal-Decompile
𝘋𝘦𝘤𝘰𝘮𝘱𝘪𝘭𝘦 𝘢𝘯𝘺 𝘱𝘺𝘵𝘩𝘰𝘯 𝘴𝘤𝘳𝘪𝘱𝘵 𝘴𝘵𝘢𝘳𝘵𝘪𝘯𝘨 𝘸𝘪𝘵𝘩 𝘦𝘹𝘦𝘤(𝘮𝘢𝘳𝘴𝘩𝘢𝘭.𝘭𝘰𝘢𝘥𝘴(...
𝘸𝘰𝘳𝘬𝘴 𝘸𝘪𝘵𝘩 𝘗𝘺𝘵𝘩𝘰𝘯 2.𝘟 𝘵𝘰 3.9
𝘶𝘴𝘪𝘯𝘨 𝘶𝘯𝘤𝘰𝘮𝘱𝘺𝘭𝘦6 (𝘗𝘺𝘵𝘩𝘰𝘯 < 3.7) 𝘢𝘯𝘥 𝘥𝘦𝘤𝘰𝘮𝘱𝘺𝘭𝘦3 (𝘗𝘺𝘵𝘩𝘰𝘯 >= 3.7)
[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Neuton&size=25&color=30FF40&background=000000&center=true&vCenter=true&width=360&height=60&lines=Hello+World%2C+Farhan-XD+Here;today+I+will+tell+you+;how+to+decompile+marshal+scripts+%3Av)](https://git.io/typing-svg)
# Installation
```
pip install uncompyle6
pip install decompyle3
```

# Usage

𝘨𝘪𝘷𝘦𝘯 𝘢 𝘧𝘪𝘭𝘦 𝘯𝘢𝘮𝘦𝘥 "𝘮𝘢𝘳𝘴𝘩𝘢𝘭𝘦𝘥𝘍𝘪𝘭𝘦.𝘱𝘺" 𝘭𝘪𝘬𝘦

```python
#!/usr/bin/env python
import marshal
exec(marshal.loads('c\x00\x00\x00\x00\x00\x00\x00\x00\x02\x00\x00\x00@\x00\x00\x00s\x90\x00\x00\x00d...
```

𝘤𝘢𝘭𝘭
```
python2 marshaledFile.py 27
```
𝘖𝘶𝘵𝘱𝘶𝘵
```
unmarshal/decompile Python
open file marshaledFile.py
decompile Python 2.7 code with Python 2.7
write decompiled code to marshaledFile_decompiled.py
```


# or

𝘨𝘪𝘷𝘦𝘯 𝘢 𝘧𝘪𝘭𝘦 𝘯𝘢𝘮𝘦𝘥 "𝘮𝘢𝘳𝘴𝘩𝘢𝘭𝘦𝘥𝘍𝘪𝘭𝘦38.𝘱𝘺" 𝘭𝘪𝘬𝘦

```python
#!/usr/bin/env python
import marshal
exec(marshal.loads(b'c\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x02\x00\x00\x00@...
```

𝘤𝘢𝘭𝘭
```
python3 marshaledFile.py 38
```
𝘖𝘶𝘵𝘱𝘶𝘵
```
unmarshal/decompile Python
open file marshaledFile38.py
decompile Python 3.8 code with Python 3.9
write decompiled code to marshaledFile38_decompiled.py
```

𝘸𝘩𝘪𝘤𝘩 𝘸𝘪𝘭𝘭 𝘭𝘰𝘰𝘬 𝘭𝘪𝘬𝘦
```python
# decompyle3 version 3.8.0
# Python bytecode 3.8
# Decompiled from: Python 3.8.2 (tags/v3.8.2:7b3ab59, Feb 25 2020, 23:03:10) [MSC v.1916 64 bit (AMD64)]
# Embedded file name: <source>

def test():
    return 0

print(test())
```
