# SuperStudent

A fast and minimal app that brings together essential student info from places like *veacross*, *schedules*, *canvas*, *g suite* etc 
and uses ***Fuzzy Finders*** to make the most relevent information available as quickly and easily as possible.

## Usage

Currently, we are in a very early alpha stage. I plan to package it as an app when I haave time, but for now you can use the following
commands in any bash or zsh terminal to download and run SuperStudent. Please don't try to build it yourself, it requires some strange compiler flags,
toolchains, dependancies, and other stuff depending not just on your platform but other parts of your computer specifically. It is best just to let the
run scripts take care of it for you.

to run:
    - Mac
```bash
curl -s -L https://raw.githubusercontent.com/MrQuasar173/superstudent/main/run-mac.sh | bash
```
    - Linux
```bash
curl -s -L https://raw.githubusercontent.com/MrQuasar173/superstudent/main/run-linux.sh | bash
```

Note: Things work a bit better on linux than on mac. For both, please ensure that python 3 is installed.

## TO DO

    * Package as app in AUR, flatpack, and for mac
    * Make a GUI frontend
    * Make API for google chat bot
