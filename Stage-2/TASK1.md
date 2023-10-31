# TASK-1 (STAGE-2)

Well, my fellow explorers, it is crazy that you all made it to STAGE-2 of this wonderful Open-Souce Cryptic Hunt. The task will be a bit difficult from now on, but I am sure you will clear it. Explorers, fight for your positions and win cash prizes.
Wishing all my fellow explorers ALL THE VERY BEST!

# TASK INSTRUCTIONS:

This is your 1st task of the Open Source Cryptic Hunt (Stage 2)!

"Explore the hidden treasures within images, unveiling valuable information and intricate details beyond the surface."

<img src="https://github.com/Mrpai2318/OSCH-23-Solutions/blob/main/Stage-2/_resources/n0k14%203310.jpg" alt="nokia img">

Download: https://t.ly/QHTAc

# Solution
The solution to this challenge is a little tricky if you solve the riddle you will get a hint that the image metadata has to be extracted so if we use any online metadata extractor you will get the hidden links and hints that are behind an image.

<img src="https://github.com/Mrpai2318/OSCH-23-Solutions/blob/main/Stage-2/_resources/metadata.png" alt="metadataimg">

If you search the metadata of the image, you will find 2 things: one is a drive link, and the other is a hint to what is present in the drive link.

**https://docs.google.com/document/d/1Oj45TJXmTkwO5CerUzle_rQu3GYiRPCATaBLwZvI1Wk/edit?usp=sharing**

**NOKIA Loves Vigenere**

Vigenere is a cipher more on that [<ins>here</ins>](https://t.ly/fI1Xu).

So, using these 2 hints, you can decode the encrypted text given in the Google doc using the key NOKIA.

<img src="https://github.com/Mrpai2318/OSCH-23-Solutions/blob/main/Stage-2/_resources/decode.png" alt="vigenerecipher">

This takes you to a YouTube link.
https://www.youtube.com/watch?v=N0nvCHBN3lE&ab_channel=shashank%40dev

Here, if you see comments, you will find 2 accounts that seem kinda sus.

<img src="https://github.com/Mrpai2318/OSCH-23-Solutions/blob/main/Stage-2/_resources/youtubess1.png" alt="youtubess">

If you open foss-n0k14 which is actually a distraction, you will get an account of which the description is **44 2 0 44 2 0 999 666 88 0 4 666 8 0 8 777 444 222 55 33 3** now this relates to the keypad on nokia phones which used the old way of typing messages where we had to press numbers multiple times to get to the letter that we wanted.

If you decode this, you will get something that says **HA HA YOU GOT TRICKED**

If you open the 2nd account NOKIA_3310
You will get this:-

<img src="https://github.com/Mrpai2318/OSCH-23-Solutions/blob/main/Stage-2/_resources/youtubess2.png" alt="youtubess2">

If you decode this:-
**8 44 33
2 66 7777 9 33 777 
444 7777
3 444 2 555
66
333 666 777
66 666 7777 8 2 555 4 444 2**

You will get:-
**THE
ANSWER
IS
DIAL
N
FOR
NOSTALGIA**

The final answer and the password to open TASK 2 is:- **DIAL N FOR NOSTALGIA**
