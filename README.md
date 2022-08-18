# Entelect University Cup 2022
This is my  solution for the 2022 Entelect University cup PRACTICE ROUND, which is a decoding challenge.

How to run
```
git clone https://github.com/rohanday3/entelect-practice-2022 && cd entelect-practice-2022
pip install -r requirements.txt
python main.py <map-file>
```
## Architecture
There are 3 python files, namely main.py, map.py and tile.py.
### main.py
Reads in the map.
Creates the tile and map objects
### map.py
Map class which creates a 2d array of tile objects
### tile
Tile class which calculates the type of terrain
