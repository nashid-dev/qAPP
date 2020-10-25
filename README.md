# qAPP

بِسْمِ ٱللّٰهِ الرَّحْمٰنِ الرَّحِيْمِ ,
السَّلاَمُ عَلَيْكُمْ وَرَحْمَةُ اللهِ وَبَرَكَاتُهُ

qAPP is an easy to use quran reader with support for translation in multiple languages . Made with Qt5 .

Inspired by the Discord IslamBot Project (https://github.com/galacticwarrior9/IslamBot)

**Dependencies**

`libcurl4-openssl-dev , qt5-default, nlohmann json`
* libcurl installation = `sudo apt install libcurl4-openssl-dev`
* nlohmann json = https://github.com/nlohmann/json , this repo already contain nlohmann json header so no need to clone
* Qt5 = `sudo apt install qt5-default`

**Installation**

*  Install Dependencies and follow the below steps
1. clone the repo and cd to repo folder
2. qmake
3. run `make` , it will compile the program
4. run the program `./qAPP --h`

*Note: If you get GTK-Warning failed to load canberra-gtk-module , fix it by*
`sudo apt install libcanberra-gtk-module`
