# Level 7 > 8

Goal: 
The password for the next level is stored in the file data.txt next to the word millionth

## What I Did:

- I first ran the command ls to confirm i can see data.txt
- I then used the command cat data.txt but i knew it would not be that easy! it was a large file with many words
- So to find the password, in the goal it says the password is next to the world millionth i ran the command cat data.txt | greg millionth
- Running that command filtered the file and i found the password

Password Found: dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc

![Image](images/Level7o8.png)

## What Did I Learn?

I learned in this level that when dealing with big files, it’s way easier to use grep to search for specific words instead of reading through everything manually. In this case, just running grep millionth data.txt gave me exactly what I needed.