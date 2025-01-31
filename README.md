# cprCartSurfer

Simple bot for Cart Surfer game on Club Penguin Rewritten servers.

Initially, I was going to aim for 200 coins /game, but that was too difficult to code, so instead, this bot will get a score of 40-60 while dying at every turn. But hey, it works.

From my (light) testing, it seems to generate about **163 coins per minute**.

# Demo

[![Video Demo](https://img.youtube.com/vi/xgupmvprGzY/0.jpg)](https://www.youtube.com/watch?v=xgupmvprGzY)

# Usage

* Clone this repository
    - `git clone https://github.com/AgeOfMarcus/cprCartSurfer`
    - `cd cprCartSurfer`
* Install the required packages
    - This project uses the Python language (>=3.8) with the [pyAutoGUI](https://pyautogui.readthedocs.io/en/latest/) library
    - `pip install pyautogui`
* Launch Club Penguin, and run the bot
    - `python cartSurfer.py`
    - Make sure the CPR window is visible and in focus

When capturing the images used for the on-screen element detection, my game window was not full screen. My graphics settings were also on the highest. Due to this, the program may not work at first for you.

To fix this, you can recapture and replace all images in the `images/` directory.