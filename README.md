# python-shell-beautify
**Colors and text formats for console using python**

* Import first:
```python
import shell_colors as c
```
_Usage Example:_

* Option 1 f-string:
```python
print(f"{c.red}Hello{c.end} {c.blue}World!{c.end}") 
```

* Option 2 string format:
```python
print("{}Hello{} {}World!{}".format(c.red, c.end, c.blue, c.end))
```

* Option 3 concat:
```python
print(c.red + "Hello" + c.end + " " + c.blue + "World!" + c.end) 
```

* Option... 4? 👀:
```python
print(c.red , "Hello" , c.end , c.blue , "World!" , c.end) 
```

