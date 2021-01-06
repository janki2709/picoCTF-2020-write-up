# Mr-Worldwide
Points: 200

## Category 
Cryptography

## Description
A musician left us a message. What's it mean?

## Hints
(None)

## Solution
I got the following code by opening the message.txt file  
picoCTF{(35.028309, 135.753082)(46.469391, 30.740883)(39.758949, -84.191605)(41.015137, 28.979530)(24.466667, 54.366669)(3.140853, 101.693207)_(9.005401, 38.763611)(-3.989038, -79.203560)(52.377956, 4.897070)(41.085651, -73.858467)(57.790001, -152.407227)(31.205753, 29.924526)}  
First I thought that it could be any substitute cipher but after trying I realized that it is something different.  
Then I put all these coordinates in Google Maps in the form of (longitude, latitude) and got the following city names.  
Kyoto, Japan  
Odessa, Ukraine  
Dayton, United States  
Istanbul, Turkey  
Abu Dhabi, United Arab Emirates  
Kuala Lumpur, Malaysia  
_  
Addis Ababa, Ethiophia  
Loja, Ecuador  
Amsterdam, Netherlands  
Sleepy Hollow, United States  
Kodiak, United States  
Alexandria, Egypt  
Put first letter of all the city names together to get the flag.  

## Flag
picoCTF{KODIAK_ALASKA}
