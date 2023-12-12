# Electations Scraper

## Description

Program is used to collect czech election data of the year 2017 from URL:
https://volby.cz/pls/ps2017nss/ps3?xjazyk=CZ

## Installation

A list of all need libraries can be found in file: requiremens.txt 

Install required libraries manually or use `pip install -r requirements.txt`

Before installation is recommended to create a virtual enviroment.

## Running 

To run the program two arguments are required.

First argument is URL that can be found under "X" in column "Výběr obce".

Second argument is the name of output file. Output file must be ".csv".

## Example

 - python main.py "https://volby.cz/pls/ps2017nss/ps32?xjazyk=CZ&xkraj=6&xnumnuts=4203" "vysledek_litomerice.csv"


## Output example

![Output_example](https://github.com/VaclavHa/Projekt_3_Engeto/assets/143717185/b6c83b50-d193-43e7-b956-f7f76ae3d44a)
