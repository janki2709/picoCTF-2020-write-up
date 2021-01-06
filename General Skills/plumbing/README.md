# plumbing
Points: 200

## Category 
General Skills 

## Description
Sometimes you need to handle process data outside of a file.   
Can you find a way to keep the output from this program and search for the flag?   
Connect to jupiter.challenges.picoctf.org 4427.  

## Hints
Remember the flag format is picoCTF{XXXX}  
What's a pipe? No not that kind of pipe... This http://www.linfo.org/pipes.html

## Solution
After viewing hints, it is clear that we need to use two commands.  
First one is obviously    
nc jupiter.challenges.picoctf.org 4427   
Because we need to connect to jupiter.challenges.picoctf.org 4427  
Second one should be related to something that can search for our Flag.  
So it can be   
grep picoCTF   
From the hint we need to use pipe(form of redirection) and its syntax is like  
command_1 | command_2 [| command_3 . . . ]  
So final command is  
nc jupiter.challenges.picoctf.org 4427 | grep picoCTF  
First command connects to given address and second command finds picoCTF from the output of the first command.  
![alt text](https://github.com/janki2709/picoCTF-2020-write-up/blob/master/General%20Skills/plumbing/plumbing.png)  

## Flag
picoCTF{digital_plumb3r_5ea1fbd7}


