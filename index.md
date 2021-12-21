# Technical Blogpost On my First Tool !

## Introduction

This Tool was made in the last part of the first module GPR5100 of the second year in games programming at SAE Institute. The purpose of the tool is to help the third year with everything related to gameplay values in their city building game called Volyday made on Unreal. The tool was divided in 3 parts : Data base, Simulator and Editor. The third year student referent on the tool was Solange that helped and gives feedback all along the way. For more details and to see the tool fully, here is [The manual](https://docs.google.com/document/d/1BPadEZaKvTgLMROArouL9oTvHROrz1t10AokWw_xuVY/edit#)  

## Data Base and Unreal Engine

A Data base is useful in a lot of ways, it will allow the third year to access the data everywhere in the project and change it for everyone when changed. We had free choice of the format of the data base, after researching we choose to do it on an excel file (google sheets for multiple person to work on it at the same time) We choose this because it can export the data on .csv format that unreal can easily read to make a data table.

### What's a .csv file ?

Here is what our data base looked like on google sheets 

![image](https://user-images.githubusercontent.com/71375990/146958964-a3778d8e-dede-4a72-8b84-52f52f966b41.png)

...and here is what it looks like in .csv format.

![image](https://user-images.githubusercontent.com/71375990/146959207-6cc72a3e-770f-4ee4-be71-9f252fdf87b7.png)

A Comma-separated values format like it's name implies, separate the data in our sheets by comma. But by naming the column and line our file was messed up. To fix this problem we used Data tables on unreal to name every column and line and now you can easily re-import a new data tables csv file way faster thanks to unreal.

## Simulator

Now that the database is changeable we need to know when to change it. The simulator is an excel file that takes data from the data base to simulate a fake game only with numbers and shows it to us via graphics. The simulator shows the game designer's useful graph that changes when they change the data base. With that they can adjust the difficulty and whole design of the game to their liking by tweaking numbers.

Here is a part of a simulator : 
![image](https://user-images.githubusercontent.com/71375990/146980159-55603ca1-7bda-4010-8eda-7b6a65725c34.png)

We can see that each month we have the gain and loss of a building. In the left up corner the value we see comes from the data base and is why the simulator is always up to date.

And here is a graph for a better understanding : 
![image](https://user-images.githubusercontent.com/71375990/146980750-b6c39111-257c-4572-ba6f-2f05654a475e.png)


## Conclusion 

I'm really happy and hopeful that my tool will be useful for the third grader. I'm glad I retouched excel because it's a really powerful tool that could come in handy in the future.
But could we do it better and faster ?
Yes in multiple way. First of all, I'm certain there is a way to make the simulator easier to modify and even more time saving but I don't know well exel true power.
We could also make the transfer of database to unreal way faster and automatic for more people to work on. We could make a LAN server where everyone can change the excel and unreal could read it without having to re import each time.
