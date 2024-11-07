
Vital Sign Simulator Readme 1.4.3
=================================

Installation Instructions:
--------------------------
1. Download the file "Vital Sign Simulator 1.4.2 Installer.zip"
2. Unzip THE WHOLE CONTENT (4 files) to a folder on your HDD
3. Run "setup.exe"

Note: Since the Programm was written with visual basic express, there are no installation options, sorry about that


Instructions for use:
---------------------
1.  Ideally, get a computer with a additional Monitor attached (set it to "extended desktop" or similar)
2.  To use the advanced options (defibrillation), you should attach a second keyboard. Or you could attach a second mouse and run a programm to make it independent from the first one (eg. "Pluralinput" or "Teamplayer"), so you get two mouse pointers
3.  Run Vital Sign Simulator
4.  The operator screen will appear. The Window with the vital signs for the trainees will appear behind it
5.  Drop the Training Window to the additional monitor and face it towards the trainees (and give them the second keyboard/mouse so they can operate the trainee-interface)
6.  On the operator-screen, set the desired starting values, hit "Apply"
7.  The values will appear on the Training Window screen as soon as you hit the "available"-checkbox on the operator-interface. Example: As soon as the trainees say "I attach a pulsoxymetry", hit the "sp02 available"-checkbox
8.  Vary the values according to your simulation-scenario, set the after-defibrillation-rhythm etc. etc.

Note: Ideally, you use Vital Sign Simulator on a computer with two monitors (extended desktop), and two keyboards or mice. You can even use it with a basic CPR-manikin and get the trainees to attach homemade fake BP-Cuffs, spO2-sensors and the like to get the desired vital signs.
Visit the wiki under the help menu for more information.


Version History:
----------------
V 1.4.3
Fixed variuos interactions between gradual HR-change and defibrillation/rhythm changes

V 1.4.2
Added gradual vital sign change for HR with auto-documentation
Fixed wrong caption for BP in operator window (thx to Hauke!)

V 1.4.0
Added gradual vital sign change for spO2 with auto-documentation
Fixed various language problems

V 1.3.0
Added kPa-units for etCO2 (thx to Tom for the suggestion!)
Fixed english etCO2-title and various other titles

V 1.2.0
Added function for CPR-artefacts (thx to Kiril for the suggestion!)

V 1.1.0
Added etCO2 (thx to David for the suggestion!)

V 1.0.2
Fixed unable to shock by keyboard-command while in sync-mode
Fixed joule-display disappearing
Fixed focus-problem (clicking other focused button when hitting enter)

V 1.0.1
Fixed Analyse-button on operator window not working

V 1.0
Added audio voice prompts for the AED (english and german)
Added AED-controls in the operator window
Added documentation for pressing the analyse-button
Fixed issue when analyse was pressed multiple times

V 0.9.2 beta
Icreased the range for the SpO2- and Resp.-Values for pediatric scenarios (thx to tobi for the suggestion!)
Improved interface for entering the HR, SpO2 and Resp.
Added units (eg. "bpm") to various displays (thx to carlos!)
Fixed translation errors in the spanish interface (again thx to carlos!)
Fixed german AED-instructions overlapping screen

V 0.9.1 beta
Fixed enter key not responding to trainee commands
Fixed pacer continuing pacing while loading defibrillator

V 0.9 beta
Added more documentation events
Completed the spanish interface (thanks to carlos!)
Added keyboard support (instead of second mouse)

V 0.8 beta
Changed behaviour of the pacemaker, should work more realistic now
Added scrollbars if windows are too big for the screen
Added autoscroll in the documentation section
Added an "Analyse"-button with AED-behaviour
Added a spanish interface (incomplete!)
Small changes in the "about..."-section

V 0.7 beta
Added Sounds
Improved the "Auto-HR"-Function

V o.6 beta
Added a documentation function
Added saving documentation to .rtf
Online-help added
New wiki with manual etc on sourceforge.net
Included visual basic power packs in the installation
Some translation errors fixed

V 0.5 beta
Synchronized defibrillation (cardioversion) added
Options menu (+/- defibrillator etc)
Pacer added (not yet functioning to my satisfaction...)
Improved ECG-color
Update-Link added in the Help menu
Hide training window added in the menu

V 0.4 beta
Animated ECG (Trainee-side only)!!!
Bigger ECG-screen (trainee-side)
Improved defibrillation graphics
Fixed various bugs concerning defibrillation
Added a menue-bar (not yet fully functional)
Added a "About..."-Section and the GNU-GP-License

V 0.3 beta
Added the defibrillator! (Still buggy...)
Fixed some translation errors
Fixed starting up in german
Added a delay for the NIBP (now takes time to measure, like in real life)
Added a randomizer (+/- 2mmHg) to make the NIBP look more real

V 0.2 beta
Fixed a graphics alignment error
Fixed various bugs
Added a "Display"-button for the NIBP on the operator screen

V 0.1 beta
Basic functions available

