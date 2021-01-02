# strings it
Points: 100

## Category 
General Skills

## Description
Can you find the flag in file without running it?

## Hints
https://linux.die.net/man/1/strings

## Solution
It is clear from the hint that we need to use strings command to make file readable.    
So we use "strings strings > output.txt"    
Here first strings stands for strings command   
Second strings stands for file we downloaded named strings    
We used > output.txt so that result can be stored.     
Now we can find flag in output.txt    
But to make it faster we use "grep picoCTF output.txt" command.  
grep is used to search for a string of characters in a specified file.  
Flag can be found with this command.    

## Flag
picoCTF{5tRIng5_1T_7f766a23}
