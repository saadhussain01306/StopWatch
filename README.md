# Stopwatch Web Application

[Visit-Site](https://stopwatch01306.netlify.app/)

This simple web application, named **Stopwatch Site**, provides a stopwatch functionality with a user-friendly interface. Users can start, stop, and reset the stopwatch to track elapsed time.

## Features

- **Start Button:** Initiates the stopwatch, measuring time in minutes, seconds, and tenths of a second.
- **Stop Button:** Pauses the stopwatch at its current time.
- **Reset Button:** Stops the stopwatch and resets the timer to 00:00:00.


## Code Structure

- **HTML (`index.html`):** Defines the structure of the web page, including the stopwatch display and control buttons.
- **CSS (`styles.css`):** Contains styles for the layout and appearance of the stopwatch.
- **JavaScript (`script.js`):** Implements the stopwatch functionality, including start, stop, and reset actions.

## Implementation Details

The stopwatch is implemented in JavaScript with intervals for accurate time tracking. The timer displays minutes, seconds, and tenths of a second, updating dynamically as the stopwatch runs.

### Timer Logic

- The timer increments every 10 milliseconds.
- When the tenths of a second reach 100, seconds are incremented, and the tenths reset to 0.
- Similarly, when seconds reach 60, minutes are incremented, and seconds reset to 0.

🕒
