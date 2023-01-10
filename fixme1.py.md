# fixme1.py

## Description
Author: LT 'syreal' Jones </br>
Fix the syntax error in this Python script to print the flag. 

[Download Python script](https://artifacts.picoctf.net/c/39/fixme1.py)

## Solution

Open the fixme1.py file in any editor and remove the indent from line number `20`.</br>
Previous:</br>
```
flag = str_xor(flag_enc, 'enkidu')
  print('That is correct! Here\'s your flag: ' + flag)
```
</br>
After:</br>

```
flag = str_xor(flag_enc, 'enkidu')
print('That is correct! Here\'s your flag: ' + flag)
```

## Flag
picoCTF{1nd3nt1ty_cr1515_182342f7}
