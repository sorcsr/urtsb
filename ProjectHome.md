UrTSB is a Game Server Browser for the FPS Urban Terror ( http://www.urbanterror.info ) targeted to run on Linux and Windows (Mac-Users: if you manage to get Python 2.6 and PyGTK running UrTSB should also work on MacOS).

Features:
  * server search (master server query)
  * filter results (including UrT specific gametypes)
  * display server details - players (with kills, ping) and server vars
  * manage favorites - add/remove servers to a favorites list
  * buddylist - manage a buddylist and search servers your buddies are playing on (note: the search is case sensitiv!). Supports substrings. For example if you add only the string `[clantag]` a buddysearch will return all servers where players with `[clantag]` in their name are playing. Good to see where your clanm8s are playing :)
  * of course launching Urban Terror with automatic connection to a selected server
  * view a list of servers you recently played on (if UrTSB was used to connect) inclusive date of last connection and number of connections
  * RCON feature


Looking for a screenshot of UrTSB? Follow the link: [Screenshots](Screenshots.md)

Discussion thread on the official Urban Terror Forums about UrTSB: http://forums.urbanterror.info/topic/22858-urtsb/

Dependencies:
  * Python 2.6
  * PyGTK

On Debian Sid additionaly the package [gir1.0-glib-2.0](http://packages.debian.org/de/sid/gir1.0-glib-2.0) is needed due to a bug:
http://bugs.debian.org/cgi-bin/bugreport.cgi?bug=590680
Thx to SamSpade for [pointing that out](http://forums.urbanterror.info/topic/22858-urtsb/page__view__findpost__p__278930).