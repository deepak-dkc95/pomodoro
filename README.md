# Pomodoro
Clock based on [pomodoro technique](https://en.wikipedia.org/wiki/Pomodoro_Technique) for increased focus and productivity.

## Description
The clock is designed with a start and a reset button.\
Start button - Starts the clock.\
Reset button - Resets the clock to 00:00 \
Work session - Each work session is 25 minutes.\
Short break session - Each short break session is of 5 minutes.\
Long break session - Each long break session is of 20 minutes.

### Functionality
Once the Start button is pressed a Work session starts.\
Upon completion, a Tickmark appears between two buttons. \
A Short break session follows it. \
The cycle repeats 3 times. \
After the 4th Work session, a Long break session starts. \
The cycle continues until the Reset button is clicked.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install Tkinter.

```bash
pip install tk
```

## Usage

```python
#import statement
import tkinter

# creates a GUI window
window = tkinter.Tk()

# creates a button
button = tkinter.Button(command=function)
```
