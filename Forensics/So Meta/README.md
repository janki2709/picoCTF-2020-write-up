# So Meta 
Points: 150

## Category 
Forensics 

## Description
Find the flag in this picture.

## Hints
What does meta mean in the context of files?  
Ever heard of metadata?

## Solution
It is clear from the hint that we need to check metadata of the file.  
So we will Install exiftool using following command  
sudo apt install libimage-exiftool-perl  
Now use following command to extract metadata  
exiftool pico_img.png  
Flag can be found in Artist field  

## Flag
picoCTF{s0_m3ta_d8944929}


