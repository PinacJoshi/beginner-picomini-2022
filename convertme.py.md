# Convertme.py

## Description
Run the Python script and convert the given number from decimal to binary to get the flag. 
* [Download Python script](https://artifacts.picoctf.net/c/31/convertme.py)

## Solution
Use `wget` command in your preferred directory to retrive the files:

`wget https://artifacts.picoctf.net/c/31/convertme.py`

You can use `ls` command to list the files.
Run to execute the given file simply run:

`python3 convertme.py`

After executing the file it should show you the following output:

```
python3 convertme.py
If 94 is in decimal base, what is it in binary base?
Answer:
```

In my case it showed me `94` but in your case it might show something else.

To convert it to binary base you can simply search on google for a convertor or you can use this one that I found [Link](https://www.rapidtables.com/convert/number/base-converter.html)

Enter the number that you got in your case and select the "to base" field to binary. In my case it was like this:

![alt text](/home/coldbrew/Documents/CTF/beginner-picomini-2022/images/base10tobase2.png)

You can then simply click the copy button and paste the answer in the terminal.

`If 94 is in decimal base, what is it in binary base?`
`Answer: 1011110`
`That is correct! Here's your flag: picoCTF{4ll_y0ur_b4535_9c3b7d4d}`

## Thoughts
I don't know why but I struggled in this challenge. I tried to use my favourite tool called cyber chef to try and convert it to binary but unfortunately I found out that cyber chef converts it one by one that means if we entered '19' it would convert the 1 and the 9 seperately, thus the struggle.

## Flag
picoCTF{4ll_y0ur_b4535_9c3b7d4d}
