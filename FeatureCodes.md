# Telemedia Feature Codes

### General

`*200` -    VoicemailMain

`*201` -    Record Voice Prompt (# to save) (saved to /var/www/html/sounds/)

`*202` -    Call Pickup (features.conf) - *** DEPRECATED ***

`*203` -    Forward All Calls (variable number) - Enable & Disable

`*204` -    Forward All Calls (pre-programmed number) - Number Setup

`*205` -    Forward All Calls (pre-programmed number) - Enable & Disable

`*206` -    Listen In

`*207` -    Pickup Channel - *** DEPRECATED ***

`*208` -    (BETA) - Enable divert to destination at the CLI level (individually) rather than company level  
        
* **Syntax**: `*208*{3 digit destination}*{destination number}*{CLI to apply to}`
* **Implementaion**: The above feature code should inserted as a speed dial on an extension's keys
* **Example**: `*208*vms*890*+441618509122` (This will send all calls for +441618509122 to voicemail box 890)
* **Example**: `*208*grp*821*+441618509122` (This will send all calls for +441618509122 to group 821)

### Hotdesk

`*220` -    Hotdesk Login

`*221` -    Hotdesk Logout

`*222` -    Hotdesk Admin Logout (PIN = 7510)

### Relay Switches

`*291` -    Realy1 On/Off

`*292` -    Realy2 On/Off

`*293` -    Realy3 On/Off

`*294` -    Realy4 On/Off

`*295` -    TCP Client app to send signal to rPi Bridge relay

### Tech

`*299` -    Echo Test

### Conference

`*210` -     Conference Room 1

`*211` -     Conference Room 2

`*212` -     Conference Room 3

### Transfer

`*1` - Cancel transfer or 3 way conf

`*2` - Transfer

`*3` - Complete 3 way conf

### Recording

`#1` - Pause Recording

`#3` - Unpause Recording

### DND

`*78` - Enable DND

`*79` - Disable DND

### Presence

`*300{EXT}` - Available

`*301{EXT}` - Break

`*302{EXT}` - Admin

`*303{EXT}` - Meeting

`*304{EXT}` - Unavailable