# Fixme2.py

## Description
*Author: LT 'syreal' Jones*
Fix the syntax error in the Python script to print the flag. Download Python script.</br>
[Download Python Script](https://artifacts.picoctf.net/c/65/fixme2.py)

## Solution
Open the file in any editor and change the line number `22` to</br> `if flag = ''`
</br>
Previous:

```
if flag = "":
  print('String XOR encountered a problem, quitting.')
```
</br>
After:

```
if flag == "":
  print('String XOR encountered a problem, quitting.')
```

## Flag
picoCTF{3qu4l1ty_n0t_4551gnm3nt_e8814d03}
