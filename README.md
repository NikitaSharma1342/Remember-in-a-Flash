# Remember-in-a-Flash

A memorizing game with the help of flash cards.

# Table of Contents

* Description
* Libraries
* How to run
* Screenshots

# Description

This application is created with the use of libraries and modules. In the application functions like flip card and next card is created to flip the card and change the card. The images used in this application are saved in the folder named as images. The data of commomly used French words are derived from the [link](https://en.wiktionary.org/wiki/Wiktionary:Frequency_lists#French) and saved in a csv file named `french_words.csv`.

# Libraries

* Tkinter
* Pandas
* Random

# How to Run

As soon as the user runs the code a window opens with a french word. If the user knows the meaning of the word then the user can click on the tick mark with in 3 seconds. After 3 seconds the card will flip and reveal its meaning in English. If after this user clicks on cross button, the word with the meaning will be saved in a csv file named as `words_to_learn.csv`.

The next time, the user uses this application the words would be taken from `words_to_learn.csv`.

# Screenshots

* Opening Window

<img width="672" alt="image" src="https://user-images.githubusercontent.com/103064401/188808259-f6b5b26b-3748-4782-8f96-0f7aa2faa946.png">


* After flipping the card

<img width="674" alt="image" src="https://user-images.githubusercontent.com/103064401/188807998-0aa2f2d4-ec0c-49a2-baef-4af800e3c7a4.png">
