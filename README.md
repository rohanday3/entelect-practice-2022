# Entelect University Cup 2022
This is my  solution for the 2022 Entelect University cup PRACTICE ROUND, which is a decoding challenge.

## Problem Description

Develop a solution to decode the map and identify the hidden numbers.

There are four different terrain types and each terrain type has a different elevation range.

There will be three different maps to decipher.

## How to run
```
git clone https://github.com/rohanday3/entelect-practice-2022 && cd entelect-practice-2022
pip install -r requirements.txt
python main.py <map-file>
```
## Architecture
There are 3 python files, namely main.py, map.py and tile.py.
### main.py (RUNNER)
- Reads in the map.
- Creates the tile and map objects
### map.py (CLASS FILE)
- Map class which creates a 2d array of tile objects
### tile.py (CLASS FILE)
- Tile class which calculates the type of terrain

## Conclusion
### Map 1 (Small : 15*30)
![MAP 1](https://github.com/rohanday3/entelect-practice-2022/blob/main/1.png)
> "91"

### Map 2 (Medium : 30*60)
![MAP 1](https://github.com/rohanday3/entelect-practice-2022/blob/main/2.png)
> "07"

### Map 3 (Large : 60*120)
![MAP 1](https://github.com/rohanday3/entelect-practice-2022/blob/main/3_1.png)
> "79"
