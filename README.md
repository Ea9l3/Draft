# NSA-Code-Breaker-Challenge-2019
NSA Code Breaker Challenge 2019-Task 7 Crack

This is a python script which I used to successfully crack Task 7 of the NSA Code Breaker Challenge 2019.
This script can be run using Python 2.7. Also, requires users install PyCrypto package. 

Upon reaching Task 7, users by now will have obtained important clues and pieces of information from previous tasks which are required 
for the successful completion of the current task. 

Inputing the target's public key, saved as target.key file, executable keygen (provided as a clue upon reaching Task 7), PIN number obtained from Task 4, target XNAME from clientDB.db field, 
the script will factor the P and Q using Yafu. The P and Q is then entered in the according fields, and the script is run once again
to generate the output necessary to gain full administrative access to the Terror Time app. 

Note: the script, target.key, executable keygen, and clientDB.db must all be in the same folder in order for the python script to work.
Also, the NSA Code Breaker Challenge 2019 ended January, 2020, so the servers running the TerrorTime application are no longer accessible,
thus, this script is for research purposes only, but given all other pieces of informaiton are available will demonstrate to users how Task 7
could be completed and goes to show the power of python.

Thanks to "devilishsuzu" for writing and sharing this script, whom I had the pleasure of collaborating with on this challenge. 
