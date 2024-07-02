# Introduction to stdpopsim Workshop

## Setup for Workshop

Important!
At least 15 minutes before the workshop:
1. Click the JupyterHub link (provided to you separately)
2. Log in with your user name 
   - your user name is your email address
   - your password will be whatever you first input as a password
3. In the top right corner click "New" -> "terminal" (this will open a terminal window)
4. Clone the GitHub repository
```
git clone https://github.com/popsim-consortium/workshops.git
```
*Note:* If you are asked for username/password when cloning the repository,
double-check the URL - you probably have a typo.

## Local setup (on your own machine) if you like

We have created a `conda` environment that allows you to install
everything you need to run this workshop without the virtual server. 
Assuming you have `git` installed, start by cloning the repo
```
git clone https://github.com/popsim-consortium/workshops.git
```
then `cd` into that dir, and use `conda` to create the stdpopsim-environment
virtual environment for running the materials
```
cd workshops
conda env create -f environment.yml
```
This will download and install all the needed software. 
Activate the newly create environment and fire up a jupyter lab instance
to go through the materials. 

### Screen setup

In this workshop we will be using four different windows - 
The zoom call, the GitHub and JupyterHub, the stdpopsim catalog, and Slack.
We highly recommend during the workshop participants have two monitors available. 
If you only have one monitor available, you may choose to flip through the necessary windows,
or you can have all four windows up at once. 
Here is a recommendation on how to arrange your screen with all four windows.

![](images/workshop_windows.png)

-------------------------
**Short Summary of topic:** In this free, hands on workshop we will go over the basics of using the stdpopsim library to simulate published demographic models from a variety of organisms. We will cover how to navigate the library catalog, how to simulate using the Python API and command line interface, and an example analysis on the simulated data.

**Requirements:** An internet browser

**Recommended prerequisites:** Basic Unix command line and Python.

**Code of Conduct**
https://github.com/popsim-consortium/stdpopsim/blob/master/CODE_OF_CONDUCT.md

--------------------------
## Resources
- Binder link to use Jupyter Notebook [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/popsim-consortium/workshops.git/main?filepath=intro_stdpopsim%2FIntro_stdpopsim.ipynb)
- [stdpopsim Documentation](https://stdpopsim.readthedocs.io/en/stable/index.html)
- [stdpopsim GitHub](https://github.com/popsim-consortium/stdpopsim)

--------------------------
## How to install locally
Not recommended for the workshop, unless you are experienced with installing Python packages.

Follow the [conda](https://stdpopsim.readthedocs.io/en/stable/installation.html#conda) or [pip](https://stdpopsim.readthedocs.io/en/stable/installation.html#pip) installation documentation.
In addition you will need to install the other packages listed in the [environment.yml](https://github.com/popsim-consortium/workshops/blob/main/environment.yml).

--------------------------
## Recording link from Previous workshops
Workshop 1, October 26 2020, Instructor: Ariella Gladstein  
https://uoregon.zoom.us/rec/share/PWU57vtDTqbleYdAbuD0oiQIKfc2cq75Y6jd8uPO-fAXvyHuWS2n-sMq5I3EH1gH.dID6FaAy19XRzX49 
Passcode: +Ej57x1Z 

Workshop 3, December 9 2020, Instructor: Andrew Kern
https://uoregon.zoom.us/rec/share/kRLFZ79l91cQjxEfQGFIi7dh4uPLWCJbVx-Q4UcRGusxC7O9WFxnFavM9u8o8cfb.0h9vzQsHR5okoviD 
Passcode: D#uHH#2X 
