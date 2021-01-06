# extensions
Points: 150

## Category 
Forensics

## Description
This is a really weird text file TXT? Can you find the flag?

## Hints
How do operating systems know what kind of file it is? (It's not just the ending!   
Make sure to submit the flag as picoCTF{XXXXX}

## Solution
We can use Hex editor to check the file extension.
Open the file in HxD hex editor. We can see in the Decoded text section that it is a PNG file.   
In kali linux, we can use file command to check the same thing. (Screenshot is included)  
Now, we know that the data is in PNG file format so we just need to change the file extension to PNG in order to get the flag.  
Open PNG image to get the flag.

Flag
picoCTF{now_you_know_about_extensions}
