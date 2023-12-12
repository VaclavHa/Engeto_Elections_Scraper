# Electations Scraper

## Description

Program is used to collect czech election data of the year 2017 from URL:
https://volby.cz/pls/ps2017nss/ps3?xjazyk=CZ

## Installation

A list of all need libraries can be found in file: requirement.txt 

Install required libraries manually or use `pip install -r requirements. txt`.

Before installation is recommended to create a virtual enviroment.

## Running 

To run the program two arguments are required.

First argument is URL that can be found under "X" in column "Výběr obce".

Second argument is the name of output file. Output file must be ".csv".

## Example

 - python main.py "https://volby.cz/pls/ps2017nss/ps32?xjazyk=CZ&xkraj=6&xnumnuts=4203" "vysledek_litomerice.csv"


## Output example

<img alt="Output file opened in Excel" height="auto" src="[C:\Users\uzivatel\OneDrive\Desktop\Output_example.png](https://github.com/VaclavHa/Projekt_3_Engeto/blob/master/Output_example.png)https://github.com/VaclavHa/Projekt_3_Engeto/blob/master/Output_example.png" title="Output example" width="auto"/>
