# python-shell-beautify
Colors and text formats for console using python

example:

import shell_colors as c

option 1 f-string:\n
print(f"{c.red}Hello{c.end} {c.blue}World!{c.end}")

option 2 string format:\n
print("{}Hello{} {}World!{}".format(c.red, c.end, c.blue, c.end))

option 3 concat:
print(c.red + "Hello" + c.end + " " + c.blue + "World!" + c.end)

option... 4? 👀:
print(c.red , "Hello" , c.end , c.blue , "World!" , c.end)

