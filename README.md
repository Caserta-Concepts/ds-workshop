# Data Summit 2015 - Data Science Workshop

##Data and Exercises:
Please download the files under labPython and 

##Installation:
If you don't have Python or iPython installed, follow the instructions below (from the appropriate step):

###MAC or Linux users:

```
sudo apt-get install python2.7
#sudo dpkg --configure -a - needed in case dpkg not configured
sudo apt-get install python2.7
sudo apt-get install python-pip
sudo pip install pandas
sudo apt-get install build-essential python-dev python-setuptools python-numpy python-scipy libatlas-dev libatlas3gf-base
sudo apt-get install python-matplotlib
sudo pip install -U scikit-learn
sudo apt-get install ipython
sudo apt-get install ipython-notebook

Navigate to the directory "labPython"
On the command prompt start by typing - ipython notebook
```

###Windows users: 
```
1- Install python using python-2.7.7.amd64.msi present in windows folder.
2- After installation goto C:\Windows\System32
3- Right click on 'cmd' and run as administrator.

All installations should be done in administrator mode.

4- Install pip - pip can be installed using get-pip.py file present in windows folder.
5- Navigate to the folder in the command prompt where you have downloaded get-pip.py and run the following command python get-pip.py
6- Now run - python C:\Python27\Tools\Scripts\win_add2path.py - To add pip to path - pip works only if the command prompt is in admin mode.
7- Close the terminal and again open it in administrator mode(following the steps described above)
8- Run VCForpython27.msi setup present in windows folder.
9- pip install pandas
10- pip install "ipython[notebook]"
11- pip install scipy - works on only those systems which have BLAS,LAPACK and ATLAS libraries(details scipy installation details - http://www.scipy.org/scipylib/building/windows.html#blas-lapack-and-atlas)
12- pip install pyparsing ## prerequisite for matplotlib
13- Install matplotlib using matplotlib-1.4.3.win-amd64-py2.7.exe  present in windows folder.
14- pip install -U scikit-learn

Navigate to the directory "labPython"
On the command prompt start by typing - ipython notebook
```
