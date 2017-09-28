# automautist-hass
I have been programming a dynamic auticoach in Perl before I went HASS. Memory card crashes on the Raspberry PI can be a pain.

Various modules which I programmed back then will be used in the front-end interface of this auticoach.
This auticoach is based upon open-source domotica called Home Assistant, it however does not have multiple user support and modules which assist users with autism/adhd/MS/Alzheimer etc..
The front-end includes a paperless document manager, pay your bills module, track your times with camera, direct aid assist, monitoring for aid-workers, security towards the backend and multi-user overview etc..

I will not publicize the front-end yet for various reasons.

Gunther Voet, Freaking Wildchild.

This current version supports (HASS Backend):
 
 <b>Dashboard</b>
 The dashboard offers a general overview for the user.
 
 - Registration of Mental State (5 point scale: Fine, Nervous, Coping, Bail-Out, Meltdown, Crashing)
 - Assistance Required: sends a message to specific (groups of) person(s) to aid in need
 - What the user is currently doing (which will effect alerts to the user)
 - Alarm Panel access
 - Mental Times (offering you all info about the day from sunrise till sunset)
 - Weather Information (with quick clothes selector, no more warm clothes in warm weather)
 - House Health (monitoring temperatures, thermostat, ..)
 - Battery Health (of all devices)
 - Life Support (all the meetings needed to structure, which is synchronized with my IOS calendar)
 - Home Routines (using light to warn when it is needed to start/quit)
 - Amount of bicycles available in my area
 
 - Basic Interface (removing all windows which are not needed for guest use)
 
 <b>Domotica</b>
 Because the auticoach uses light (and later sound) to warn the user, it can also be used for comfort.
 
 - All lights in the rooms 
 - House overrides (PIR detection time and room dynamics)
 - Switches
 
 <b>Alarm Panel</b>
 The motion detectors and magnetic sensors can be used to secure the premises as well.
 
 - Alarm Status (PIR units, front and back window, global alert)
 - Alarm Activity (last activity of above units)
 - Last Status (and changes by the user)
 
 <b>Green Energy</b>
 I want the coach to think for me, when I forget the lights for example..
 
 - Motion sensors will turn on/off lights after a set amount of minutes
 - Lights will never stay on for more than X time (Maximal Saving)
 - System overrides for comfort
 
 <b>Network Status</b>
 
 - The computers
 - Devices on-line
 - Owner Tracking (for aid with assist)
 - Family Tracking (for aid with assist)
 - Battery Tracking (of all devices)
 - Speedtest
 
 <b>Custom Panel</b>
 This contains all which was too much in previous screens.
 
 - Health summary (containing general summary of the user)
 - LED Lights (a list of all lights)
 - Scene Shortcuts (to make it cozier)
 - AutoMAutist Health (monitoring various units for connectivity)
 - Remote Controller (status of remote controls)
 - Binary Inputs (through the Raspberry PI)
