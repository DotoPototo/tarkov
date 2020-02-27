# Tarkov Optimisation Guide

**This is a generic guide, not all of these changes are guaranteed to make a difference. There is nothing particularly extreme about these changes but I cannot account for any harm you do to your PC. IF IN DOUBT, LEAVE IT ALONE.**

---

## 1) Update your drivers

It's obvious but update your drivers. Running the latest driver means you're getting the latest optimsations for the games you play.

## 2) In game settings

In game settings are going to make an obvious difference to your experience. I personally recommend playing with Chromatic Aberrations, Noise, Z-Blur and Grass Shadows turned off. Addionally set sensible choices for Overall Visibility and Shadow Visibility. Finally, play in fullscreen mode and with vsync off. Windowed is more convenient but it can make a slight difference to performance and vsync can add input lag;

> When an application runs in fullscreen mode, it runs in "exclusive mode". That means it has full and direct control over the screen output. 
>
> But when it runs in window mode, it needs to send its output to the window manager (windows explorer) which then manages where on the screen that output is drawn. This takes some additional performance. The performance penalty, however, is greatly reduced in newer version of windows.
>
> [- Philiip from Stack Overflow](https://gaming.stackexchange.com/questions/107028/is-there-a-difference-between-running-games-in-windowed-or-fullscreen-mode)

## 3) Alt-tabbing

A problem that can occure with playing fullscreen is performance issues from excessive alt-tabbing. A solution I personally find works for me is to create another desktop (task view button next to the start menu and then create a second desktop at the top) and then cycle between the desktop with your game and the desktop with the application you want to check using `ctrl + win key + left/right arrow key`.

If you have a multi monitor setup and you want an app on one screen with the game on the other, but then be able to see and interact with the app when you switch desktops, then in the task view right click the app and select `Show this window on all desktops`. No alt-tabbling required!

## 4) Windows power options

Open up windows settings (start menu -> settings), search `power` and select `Power & sleep settings`. On the right hand menu select `Additional power settings` and then ensure `High Performance` is selected (may be under `Show additional plans`).

## 5) Windows game mode

Windows game mode is weird, can have undersired effects or seemingly do nothing at all. A quick google provides enough talk about this. Recommendation: turn it off. 

To do this open settings, search for `Game Mode`, select `Game mode settings`, and turn off game mode. From here, select `Game bar` from the left hand menu and turn that off too.

## 6) Turn off background apps

To do this open settings, search for `background apps`, select `Background apps`, and turn off for all.

## 7) Disable full screen optimations and high dpi

Another quick google shows plenty of reports from people saying Microsofts full screen optimisations are not as great as intended, can affect fps and have other undesired effects. 

To turn it off, navigate to where the game is installed (emphasis on the game and not the launcher), right click on `EscapeFromTarkov.exe` and select properties, slect the compatability tab and check the box that reads `Disable full screen optimsations`. Then press the `Change high DPI settings` button and tick `Override high DPI scaling behaviour`.

This can also, for some people, help reduce fps drop when looking down scopes.

## 8) Set the tarkov process to high priority

When the game is running, open task manager and select the `details` tab. Find in the list the game application (not the launcher) `EscapeFromTarkov.exe` and set the priority to high. **DO NOT SET TO REALTIME**. This resets on every game exit, to save the setting permanently use [Process Hacker](https://processhacker.sourceforge.io/).

## 9) Other

Run the game on an SSD, it'll make a huge difference in load times. Close any other apps you don't need. Don't have a ton of chrome tabs open. All the usual stuff.

---

If you have any suggestions, disagree with something, or just want to tell me anything at all then let me know with an issue.
