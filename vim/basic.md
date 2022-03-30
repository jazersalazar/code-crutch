# VIM/NVIM Basics

## Mode

```
i = insert before the curso
I = insert before the line
a = append after the cursor
A = append after the line
esc/ctrl-c = edit mode 
```

## Navigation

document
```
gg - takes you to the beginning of the document
G - takes you to the end of the document
[line number]G - takes you to specific line
e.g.
Go to line 2 with 2G
```

character
```
h = left
j = down
k = up
l = right
```

word
```
b = beginning of the current/previous word
e = ending of the current/next word
w = beginning of the next word

// Can be combination with `nubmer`
`3w` is the same as pressing w three times.
```

delete
```
x = delete character
dw = delete word
dw = delete til end of line.
```
motion
```
w - start of the next word
e - end of the current word
^ - start of the line (after whitepace)
0 - start of the line
$ - end of the line
```

Search
```
f/F - find and move to the next or previous occurence of a character
e.g.
fo - find the next `o`
Fo - find the previous `o`
3fq - find 3rd occurence of `q`
---
% - go to matching parentheses

* - find the next occurence of the word
# - find the previous occurence of the word
```

Change Command
```
operator [number] motion

operator - is what to do, such as `d` for delete
[number] - is an optional count to repeat the motion
motion - moves over the text to operate on, such as `w (word)`, 
`$ (to the end of the line)`, etc.
```

Undo
```
u - to undo previous action
U - to undo all the changes on a line
CTRL+R - redo the previous action
```

Paste
```
p - paste below the line
P - paste above the lien
```

Replace
```
r[character] - replace character at the cursor with [character]
```

Change
```
ce - change until the end of a word
```
