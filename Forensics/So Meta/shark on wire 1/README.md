# shark on wire 1
Points: 150

## Category 
Forensics 

## Description
We found this packet capture. Recover the flag.

## Hints
Try using a tool like Wireshark  
What are streams?

## Solution
It is clear from the hint that we need to use Wireshark   
So I opened file in the wireshark and tried to follow streams  
but the data seems to be junk   
So We need to think in other way   
I tried to change stream id and I found flag in 6th stream.  

## Flag
picoCTF{StaT31355_636f6e6e}


