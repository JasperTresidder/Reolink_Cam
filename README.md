# Reolink_Cam
A Python interface to view stored days on the camera, live footage, and saved clips. 


## Setup
Change the ip address, username and password in main.py  

recreate the conda environment using the yml file and conda. 
Open up linux terminal, mac terminal, or windows CMD 
make sure you have conda installed.
```bash
conda env create -f environment.yml
conda activate Cam
python3 main.py
```
You may also have to install opencv or cv2 
```bash
pip install opencv-python
```
to save clips create a folder called 'clips' in the project dictionary. 
There is a text box just below 'Save Clip' to name your file.

For saving of entire days, create a folder called 'days'
The name for the saved day will be the date. 

VLC media player is used to view live streams camera clips. 

## Preview
![Screenshot at 2022-09-17 11-14-31](https://user-images.githubusercontent.com/51917264/190851760-a9f68216-5a67-425f-94a4-f06e131fd4bc.png)

Have fun
> JT
