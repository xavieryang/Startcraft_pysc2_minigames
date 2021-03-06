

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![label](https://img.shields.io/github/issues-raw/badges/shields/website.svg)]()


# Startcraft Pysc2 Deepmind minigames creation
This repository aims to serve as a guide for opensource contributing in minigame pysc2 library for Starcraft
For minigame instalation for execution you should go to https://github.com/deepmind/pysc2 and install requirements

## Minigame task description
Minigames come as a controled environments that might be useful to exploit game features in SC2. General purpose learning system for Startcraft 2 can be a daunting task. So there is a logical option in splitting this tasks into minitask in orther to advance in research . Mini-games focus on different elements of Starcraft II Gameplay .

To investigate elements of the game in isolation, and to provide further fine-grained steps towards playing the full game, Deepmind has  built several mini-games. These are focused scenarios on small maps that have been constructed with the purpose of testing a subset of actions and/or game mechanics with a clear reward structure. Unlike the full game where the reward is just win/lose/tie, the reward structure for mini-games can reward particular behaviours (as defined in a corresponding .SC2Map file).

## Minigame introduction and Repo information
Before creating a minigame, I encourage you to run the alredy developed ones to see wich task are subdivided into each minigame as the design could be important . The minigame title gives us a description of the goal 
You might find in this repo new maps created for investigate in explotation-exploration dilema and some programming about the functions of different units .

## SentryDefense , ForceField and HallucinIce Project 

In this repo, besides information about currentminigames, you will find my own minigames development . 
In projects section you can know more about the state of the art and in docs and new_minigames folder you can find the map.
In SentryDefense, a arrowhead TerranVSProtoss Melee is proposed .
In ForceField,an imbalanced situation between Sentry and Zerg units forces sentry to use forcefield, adding terrain disposition.

![alt tag](https://github.com/SoyGema/Startcraft_pysc2_minigames/blob/master/Images/Captura%20de%20pantalla%202017-09-18%20a%20las%2020.14.14.png)

![alt tag](https://github.com/SoyGema/Startcraft_pysc2_minigames/blob/master/Images/ForceField.png)

![alt tag](Startcraft_pysc2_minigames/Images/HallucinIce.gif)

Regarding scripted agent, there is a python file with current development. Please, if you make any reasearch about it share in orther to improve current minigames development .
Please, report problems in issues if you currently find problems .

## Running ForceField in your computer 

For executing Starcraft mini-games you need to have :

* Starcraft installed in your computer
* Install pysc2 library following the instructions in https://github.com/deepmind/pysc2
* Clone/Download this repository and put ForceField map on map folder
* Add ForceField.SC2Map file to Maps file in Starcraft 2, usually in Applications>Starcraft2>Maps>minigames
* Execute the agent from your console typing :
      $ python -m pysc2.bin.agent --map ForceField
      
      
#### Tutorial
Find an ongoing  tutorial about another minigame (Defeat Roaches) at https://soygema.github.io/Startcraft_pysc2_minigames/
