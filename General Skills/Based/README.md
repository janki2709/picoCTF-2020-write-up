# Based
Points: 200

## Category 
General Skills 

## Description
To get truly 1337, you must understand different data encodings, such as hexadecimal or binary.   
Can you get the flag from this program to prove you are on the way to becoming 1337?    
Connect with nc jupiter.challenges.picoctf.org 29956.

## Hints
I hear python can convert things.  
It might help to have multiple windows open.

## Solution
First type the commmand nc jupiter.challenges.picoctf.org 29956  
We get binary data which needs to be converted to ASCII(It's pretty easy to identify binary as it only includes 0 and 1)  
Convert it using any online converter. (It is already written above the binary code so we can write from that also)  
Then I got 143 150 141 151 162. It needs to be converted to ASCII  
I observe that biggest number is 7. So guess that it should be in octal form and it was correct.  
I used online octal to ASCII converter. https://onlineasciitools.com/convert-octal-to-ascii  
Then I got 6c696d65 and this one also needs to be converted to ASCII  
By observing I guess that it should be hex value so Opened hex to ASCII converter  
https://www.dcode.fr/ascii-code  
https://www.rapidtables.com/convert/number/hex-to-ascii.html  
After submitting this answer I got the flag.

## Flag
picoCTF{learning_about_converting_values_b375bb16}
