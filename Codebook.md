# CodeBook

## Description
Run the Python script code.py in the same directory as codebook.txt.
*     Download code.py - https://artifacts.picoctf.net/c/102/code.py
*     Download codebook.txt - https://artifacts.picoctf.net/c/102/codebook.txt

## Solution

It was as easy as mentioned in the description.
We first needed to download these files locally. We can simply do this by using the `wget` command.

Choose your directory of choice and run:

`wget https://artifacts.picoctf.net/c/102/code.py`

`wget https://artifacts.picoctf.net/c/102/codebook.txt`

After downloading these files you can run the `ls` command to view if the files have been installed successfully.
To get the flag you can run:

`python3 code.py`

It will output the flag on the terminal. Simply copy and paste it in the flag box on the challenge page.

## Thoughts
This challenge was waayyyyy tooo easy. All the instructions were given in the description of the challenge. I personally thought I would have had to solve it somehow in the .py file

## Flag
picoCTF{c0d3b00k_455157_197a982c}
