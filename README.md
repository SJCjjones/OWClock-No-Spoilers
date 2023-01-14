# OWClock-No-Spoilers

![image](https://user-images.githubusercontent.com/3955124/143557890-e64ad41d-9e19-4c10-9471-c2beaa1ed49b.png)

# OWClock

This mod adds a clock overlay to Outer Wilds. It can be set to count up, or down to the sun exploding.

There's also an additional event logging system; upcoming events defined in `events.json` are displayed above the clock, turning red as they approach.
New events can be added from the pause menu (timestamp will be set to the current loop time).

## Options
 - Count Up: Counts the elapsed seconds and minutes. When off, will count down to events/the end of the loop
 - Milliseconds: For speedrunners; uses millisecond timestamps
 - Events to Display: Number of upcoming events to display
 - Event List Width: Fraction of the available resolution that the event list can take up

## KNOWN ISSUES
Running this during more intensive moments seem to sometimes cause a BSOD with CRITICAL_PROCESS_DIED (At least on my PC). If anyone has this issue (or a solution), please let me know.

## OWClock-No-Spoilers fork of OWClock
This extended version of the OWClock mod will only show events that have been discovered (based on data in the on-board computer) if that's a thing that it is possible to do.  I have never done anything like this before so this will take some time, but that's the goal at least.  Now to figure out how modding works, brb.
