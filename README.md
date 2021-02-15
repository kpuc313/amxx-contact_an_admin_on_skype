<h1 align="center">Contact an Admin on Skype v2.1</h1>

<p align="center"><img src="https://github.com/kpuc313/AMXX-Contact_an_Admin_on_Skype/blob/main/Preview/Logo.png"></p>

<br />

# :page_facing_up: Description:
This plugin allows you to contact an admin on skype with chat commands.

<br />

# :computer: Chat Commands:
**!admin**<br />
**/admin**<br />
**!skype**<br />
**/skype**<br />
**!hacker**<br />
**/hacker**

<br />

# :hammer_and_wrench: Cvars:
```
as_toggle "1" // Enable Contact an Admin on Skype [0=Disable | 1=Enable]
as_type "1" // Type of contacting [1=List with skypes | 2=Auto connect to first skype]
as_num_skypes "1" // Number of skypes in the list (Maximum allowed: 3)
	
as_admin_skype "YourSkypeHere" // Default skype for both types ("as_type")
as_admin_skype2 "YourSkypeHere2" // Only if as_num_skype is 2 or 3 in as_type 1
as_admin_skype3 "YourSkypeHere3" // Only if as_num_skype is 3 in as_type 1
	
as_motd_sec "2" // Delay in seconds to auto connect to admin skype
as_motd_message "For contact with admin press on image!" // Info message (as_type "1")
as_motd_message2 "Please wait a sec!" // Info message (as_type "2")
as_motd_message_color "white" // Messages color (words: red, green, blue... or HEX code "#fff", "#ff0000")
	
as_announce_time "60" // Time in seconds to announce about admin contact option
as_announce_message "For contact with admin write say !admin" // Announce message
```

<br />

# :handshake: Thanks to:
**independent** - The code from his permanent message to get text from pcvar.<br />
**IMBA** - Idea to open admin skype chat without press on image.<br />
**Alka** - color stock and inspiration form.

<br />

# :scroll: Changelog:
    - v1.0: First Release.
    - v2.1: Unknown.
