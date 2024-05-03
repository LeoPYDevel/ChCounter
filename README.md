# How to use? Windows:
For windows you need to open the *.exe file in the zip

# How to use? Linux:
Unfortunatelly, you need a windows emulator for run it, but yu have two alternatives.

# Run with python
First, you need to download python3 (if you don't have it):
```
sudo apt install idle3
```
When the download is finished, you need to check if pip is installed: 
```
pip --version
```
Case you don't have, install it with:
```
sudo apt install python3-pip
```
Now, go to the extracted zip folder:
```
cd number_counter
```
And execute with python3 the *.py file:
```
python3 simple_counter.py
```
# Run with wine
If you choose run with wine, you need to follow the steps:
```
sudo dpkg --add-architecture i386 && sudo apt install wine
```
After installed package run winecfg in terminal to generate configuration file. And, run command to make link the .desktop file:
```
sudo ln -s /usr/share/doc/wine/examples/wine.desktop /usr/share/applications/
```
Finally, you may right-click on an EXE file to run via “Wine Windows Program Loader” option!

