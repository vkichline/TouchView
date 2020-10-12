# TouchView, a Touch Event Visualization Tool for the Emerging Interface

This app was written using Ropg's current (10/12/2020) M5Core2 Library Branch.
Another project in the repo, [TouchGoal](https://github.com/vkichline/TouchGoal) provides goal-oriented testing of the Touch UI.
This tool displays details of events, both visually on the screen and streamed to the serial port.

* Button A toggles the display of E_MOVE events
* Button B toggles the detection of long presses
* Button C toggles the key repeat mode

The display shows the kind of event followed by:

* For gestures, the name of the gesture
* For all other events:
  * The from point
  * The to pont
  * The distance in pixels
  * The angle of movement (Up = 0)
  * The duration of the event in mS

If I had another button, I'd experiment with turning rot1 on and off.

The version of the Core2 Library this is designed to work with is currently available at https://github.com/ropg/M5Core2
