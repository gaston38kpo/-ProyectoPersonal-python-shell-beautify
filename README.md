# python-shell-beautify
Colors and text formats for console using python

_Usage Example:_

* import shell_colors as c

option 1 f-string:
* print(f"{c.red}Hello{c.end} {c.blue}World!{c.end}")

option 2 string format:
* print("{}Hello{} {}World!{}".format(c.red, c.end, c.blue, c.end))

option 3 concat:
* print(c.red + "Hello" + c.end + " " + c.blue + "World!" + c.end)

option... 4? 👀:
* print(c.red , "Hello" , c.end , c.blue , "World!" , c.end)

