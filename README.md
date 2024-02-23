What is this?
=============

River Crossing is a puzzle game for the Sugar desktop.

A farmer with a wolf, a goat, and a cabbage must cross a river by boat. The boat can carry only the farmer and a single item. If left unattended together, the wolf would eat the goat, or the goat would eat the cabbage. Your task is to get them all across the river.

How to use?
===========

River Crossing can be run on the Sugar desktop.  Please refer to;

* [How to Get Sugar on sugarlabs.org](https://sugarlabs.org/),
* [How to use Sugar](https://help.sugarlabs.org/)

How to run?
=================

Dependencies:- 
- Python >= 3.10
- PyGObject >= 3.42
- PyGame >= 2.5
  
These dependencies need to be manually installed on Debian, Ubuntu and Fedora distributions.


**Running outside Sugar**


- Install the dependencies

- Clone the repo and run -
```
git clone https://github.com/vaibhav-sangwan/river-crossing.git
cd river-crossing
python main.py
```

**Running inside Sugar**

- Open Terminal activity and change to the River Crossing activity directory
```
cd activities\RiverCrossing.activity
```
- To run
```
sugar-activity3 .
```