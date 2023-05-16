# Keylogger and Screen Scraper

This repository contains code for capturing and logging screen content and keystrokes, useful for monitoring user activity or testing software. The code utilizes keylogging and screen scraping techniques to record all the user activity on the computer.

## Features

The main features of this code include:

- Keylogging: The code captures all keystrokes typed by the user and saves them to a log file called `log.txt`. The log file contains a record of all keystrokes typed by the user, along with the name of the window in which the keystrokes were typed.

- Screen Scraper: The code captures screen content whenever the user changes the window, taking a screenshot and saving it in a folder named according to the date and time of the screenshot, with the `.png` extension.

## Installation

To install and set up the code, follow these steps:

1. Clone the repository to your local machine using `git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY`.

2. Install the required dependencies, which include Python and the `pyautogui` module.

3. Run the `keylogger.py` script to start capturing keystrokes and screen content.

## Usage

To use the code, simply run the `keylogger.py` script. The script will start capturing keystrokes and screen content immediately, and will continue running until you manually stop it.

The screenshots captured by the code will be saved in a folder named according to the date and time of the screenshot, with the `.png` extension. The log file containing keystrokes typed by the user will be saved as `log.txt`.
