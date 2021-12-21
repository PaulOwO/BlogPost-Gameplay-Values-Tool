# Technical Blogpost On my First Tool !

## Introduction

This Tool was made in the last part of the first module GPR5100 of the second year in gammes programming at SAE Institute. The purpose of the tool is to help the third year with everything related to gameplay values in their city building game called Volyday made on Unreal. The tool was divided in 3 parts : Data base, Simulator and Editor. The third year student referent on the tool was Solange that helped and gived feedback all along the way. For more details here is [The manual](https://docs.google.com/document/d/1BPadEZaKvTgLMROArouL9oTvHROrz1t10AokWw_xuVY/edit#)  

## Data Base and Unreal Engine

A Data base is useful in a lot of way, it will allow the third year to access the data everywhere in the project and change it for everyone when changed. 
We had free choice of the format of the data base, after researching we choose to do it on an exel file (google sheets for multiple person to work on it at the same time)
We choose this because it can export the data on .csv format that unreal can easely read to make a data table.

### What's a .csv file ?

Here is what our data base looked like on google sheets 

![image](https://user-images.githubusercontent.com/71375990/146958964-a3778d8e-dede-4a72-8b84-52f52f966b41.png)

and here is what it looks like in .csv format.

![image](https://user-images.githubusercontent.com/71375990/146959207-6cc72a3e-770f-4ee4-be71-9f252fdf87b7.png)

A Comma-separated values format like it's name implies, separate the data in our sheets by comma.
But by namming the column and line our file was messed up. To fix this problem we used Data tables on unreal to name every column and line and now you can easely reimport a new data tables scv file way faster thanks to unreal. 

## Simulator

Now that the database is changeable we need to know when to change it.
The simulator is and exel file that takes data from the data base to simulate a fake game only with numbers and show it to us via graphics.
The simulator show the game designers useful graph that changes when they changes the data base. With that they can adjust the difficulty of the game to their liking



## Conclusion 

But could we do it better and faster ? 

Yes in multiple way. First of all im certain there is a way to make the simulator easier to modify and even more time saving but i don't know well exel true power.
