# Keylogger and Screen Scraper

This repository contains code for capturing and logging screen content and keystrokes, useful for monitoring user activity or testing software. The code utilizes keylogging and screen scraping techniques to record all the user activity on the computer.

## Features

The main features of this code include:

- Keylogging: The code captures all keystrokes typed by the user and saves them to a log file called `log.txt`. The log file contains a record of all keystrokes typed by the user, along with the name of the window in which the keystrokes were typed.

- Screen Scraper: The code captures screen content whenever the user changes the window, taking a screenshot and saving it in a folder named according to the date and time of the screenshot, with the `.png` extension.

## Libraries

- jna-5.13.0.jar: It is a core library of JNA. JNA is a library that allows Java programs to call functions in native libraries without having to write any native code.
  
- jna-platform-5.13.0.jar: Platform-specific library that provides additional functionality for calling native functions on a specific platform. It contains code that allows Java programs to call native functions on Windows.


## Installation

To run a Java class program, you need to have a Java Development Kit (JDK) installed on your system. You can download it from [Oracle]( https://www.oracle.com/java/technologies/downloads/).

To use the code, simply run the `App.class` file using command `java App` in the same directory. The code will start capturing keystrokes and screen content immediately, and will continue running until you manually stop it.

The screenshots captured by the code will be saved in a folder named screenshot and file will be saved according to the date and time of the screenshot, with the `.png` extension. The log file containing keystrokes typed by the user will be saved as `log.txt`.

## Applications

Applications
Keyloggers and screen scrapers are software tools that can be used to monitor and record 
user activity. Keyloggers record every keystroke that a user makes, while screen scrapers 
capture screenshots of the user's screen. These tools can be used for a variety of purposes, 
including:

- Monitoring and security: Keyloggers and screen scrapers can be used to monitor 
employees' activity on company computers. This can be used to ensure that 
employees are not using company computers for personal or illegal activities. 
Keyloggers and screen scrapers can also be used to investigate security breaches. For 
example, if a company's website is hacked, the hacker may have left behind a 
keylogger or screen scraper. By analysing the data from these tools, investigators can 
learn how the hacker gained access to the system and how they were able to steal 
data.

- Digital forensics and investigation: Keyloggers and screen scrapers can be used by law 
enforcement to investigate crimes. For example, if a suspect is arrested for credit card 
fraud, investigators can use a keylogger to recover the suspect's passwords and credit 
card numbers. Screen scrapers can be used to capture screenshots of the suspect's 
computer, which can be used to gather evidence of the crime.

- Training and education: Keyloggers and screen scrapers can be used to train 
employees on how to use software or to track their progress in a training program. 
For example, a company may use a keylogger to track how long employees spend 
using a particular software program. This information can then be used to improve 
the training program or to identify employees who need additional training. Screen 
scrapers can be used to capture screenshots of the user's screen, which can then be 
used to create training materials. It can also be used as child safety system, where can 
parents can monitor their children’s activity.

## Demo 
!(Watch the video)[https://drive.google.com/file/d/1UCS339hNheiLoTQS45vSThW5GoOYYdwx/view?usp=sharing]
