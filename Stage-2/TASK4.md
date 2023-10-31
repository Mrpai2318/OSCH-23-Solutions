# TASK-4 (STAGE-2)

Oh, hey there, my fellow explorers. You guys are doing great so far. I'm glad to see you all in the final task of this year's edition of Open Source Cryptic Hunt by Team FOSSIFY. We are all happy to see that you have reached this far.

Happy solving the final task for this season of OSCH!

# TASK INSTRUCTIONS:
This is the final task of the hunt. Give it your best shot.

The task includes a set of QR codes. You’d want to reduce the QR codes to 3 specific words. Navigate your way through to get to a significant location inside the MIT campus using an unconventional mapping method.

The answer isn’t just plain text. It is a set of two float numbers.

Here is a 9x9 QR Grid.

<img src="https://github.com/Mrpai2318/OSCH-23-Solutions/blob/main/Stage-2/_resources/qrgrid.png" alt="qrgrid">

# Solution

This was the most difficult question of all. Each and every row of a QR grid gives us one word, which relates to one word but it is not that simple. Every QR in the 9x9 grid has more and more QR's inside. After scanning all the QR's, you will get 3 words given below.

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

It is an unconventional way of mapping. If you use these 3 words, you will get a location that points toward the center of Student Plaza.

<img src="https://github.com/Mrpai2318/OSCH-23-Solutions/blob/main/Stage-2/_resources/what3words.png" alt="what3words">

The final answer was a set of 2 float numbers, which are the coordinates of MIT Student Plaza:-
**13.347317297371275, 74.79331747778983**
