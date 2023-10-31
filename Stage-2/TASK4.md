# TASK-4 (STAGE-2)

Oh, hey there, my fellow explorers. You guys are doing great so far. I'm glad to see you all in the final task of this year's edition of Open Source Cryptic Hunt by Team FOSSIFY. We are all happy to see that you have reached this far.

Happy solving the final task for this season of OSCH!

# TASK INSTRUCTIONS:
This is the final task of the hunt. Give it your best shot.

The task includes a set of QR codes. You’d want to reduce the QR codes to 3 specific words. Navigate your way through to get to a significant location inside the MIT campus using an unconventional mapping method.

The answer isn’t just plain text. It is a set of two float numbers.

Here is a 9x9 QR Grid.

<img src="" alt="qrgrid">

# Solution

This was the most difficult question of all. Each and every row of a qr grid gives us one word which relates to one word but it is not that simple every qr in the 9x9 grid has more and more qr's inside. After scanning all the qr's you will get 3 words given below.

QR ROW 1) 
Goliath birdeater
Avicularia avicularia —---------> GIVES US WORD TARANTULA
Grammostola pulchra

QR ROW 2)
ತಾತ್ಪರ್ಯ
Vorgeben —--------------> GIVES US WORD PURPORTS
beweren

QR ROW 3)
gold
Palladium —--------------> GIVES US WORD NOBLE
platinum

These 3 words are used on a website called [<ins>What3Words</ins>](https://what3words.com/).

It is an uncoventional way of mapping if you use these 3 words there you will get a location which points towads the center of Student Palza.

<img src="" alt="what3words">

The final asnwer was a set of 2 float number which are the coordinates of MIT Student Plaza:-
**13.347317297371275, 74.79331747778983**