Stat 157 Project 1 - Google Spreadsheet Data Wrangling
======================================================

Introduction
------------
* Team: **David Barrera** (Curator), **Christina Ho** (Visualizer), **Roland Shen** (Presenter), **Khoa Tran** (Analyzer)
* Columns Analyzed: 'What is your learning style?', 'Have you had any personal experience in any of the following topics?'


Installation & Dependencies
---------------------------

```bash
sudo apt-get install python-numpy    
sudo apt-get install python-matplotlib    
pip install gspread    
```


Instructions
------------

First, start Virtualbox, or do `vagrant up`. Then, execute

```bash
git clone https://github.com/kqdtran/questionnaire.git    
cd questionaire    
ipython notebook --ip=0.0.0.0 --no-browser --pylab=inline
```

Then, either copy the `stat157.cfg` file (if you have one previously from your group's repo) to the current directory, 
or `cp example.cfg stat157.cfg`, and edit the `stat157.cfg` file with your Berkeley username and 
[bConnected password](https://idc.berkeley.edu/mmk/auth/index).   


Questions? Issues?
------------------

Raise them on the [Stat 157's main repo]
(https://github.com/stat157/questionnaire/issues?direction=desc&sort=created&state=open)
