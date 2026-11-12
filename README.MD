# DESKA

## Introduction
In 2011, I was in the second grade of high school and I created two games for subject *Structure and object programming* (Polish: *Programowanie strukturalne i obiektowe*): [Deska](https://github.com/adam-zielonka/deska) and [Saper](https://github.com/adam-zielonka/saper). In these lessons, we learned to program using the Pascal language.

## About this game
This game was created in January 2011. At the time I did not know anything about the procedures and the functions, so everything is in one big loop. But in April 2020 I decided to rewrite code. But writing code in `cp852` is not fully possibile in modern tools, so, I created [dos-pascal-docker](https://github.com/adam-zielonka/dos-pascal-docker) to convert code written in `utf-8` to `cp852` and build exe file using Turbo Pascal running in DosBox. 

## How to run this game?
You can go to this webiste: [Play](https://adam-zielonka.github.io/deska/), the game run via [js-dos](https://js-dos.com/)

You can also download the game from this: [Download](https://adam-zielonka.github.io/deska/DESKA.ZIP), and run in [DOSBox](https://www.dosbox.com/).

The code was written using OEM 852 character set, so if you run this game by yourself, you should remeber to change default charset using this command:

```
KEYB pl
```

## Screens

![Menu](img/deska-menu.png)
![Menu](img/deska-game.png)
