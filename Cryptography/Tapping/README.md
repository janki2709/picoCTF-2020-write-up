# Tapping
Points: 200

## Category 
Cryptography

## Description
Theres tapping coming in from the wires. What's it saying nc jupiter.challenges.picoctf.org 48247

## Hints
What kind of encoding uses dashes and dots?  
The flag is in the format PICOCTF{}

## Solution
First see the output of the command given in the description.   
nc jupiter.challenges.picoctf.org 48247  
We get .--. .. -.-. --- -.-. - ..-. { -- ----- .-. ... ...-- -.-. ----- -.. ...-- .---- ... ..-. ..- -. .---- ..--- -.... .---- ....- ...-- ---.. .---- ---.. .---- }  
This is Morse encoding. We can use online decoder to get the flag   
I used https://morsedecoder.com/ and got the flag 

## Flag
PICOCTF{M0RS3C0D31SFUN1261438181}
