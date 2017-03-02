# plugin.video.netflix

## Netflix Plugin for Kodi 18


###Prerequisites
----------------

- Kodi 18 [agile build](https://github.com/FernetMenta/kodi-agile)
- Libwidevine 1.4.8.962 (A german description how to get/install it, can be found [here](https://www.kodinerds.net/index.php/Thread/51486-Kodi-17-Inputstream-HowTo-AddOns-f%C3%BCr-Kodi-17-ab-Beta-6-aktuelle-Git-builds-Updat/))
- Inputstream.adaptive [agile branch build](https://github.com/liberty-developer/inputstream.adaptive/tree/agile)

###Functionality
----------------
- Multiple profiles
- Search Netflix (incl. suggestions)
- Netflix categories, recommendations, "my list" & continue watching
- Rate show/movie
- Add & remove to/from "my list"
- Export of complete shows & movies in local database (custom library folder can be configured, by default the .strm files are stored in `userdata/addon_data/plugin.video.netflix` )

###ToDo
----------------
- [ ] Add missing meta data for episodes/seasons (Cast, bookmark position, etc.)
- [ ] Change list of shows to actual list of episodes in the "Continue watching"" section, like it´s done on the website
- [ ] Enable possibility to export single episodes or seasons to the Library
- [ ] Evaluate idea of an auto updating library exporter that keeps track

###Error Handling
-----------------

If something doesn't work for you, please:

- Make sure all prerequisites are met
- Enable verbose logging in the plugin settings
- Enable the Debug log in you Kodi settings
- Open an issue with a titles that summarises your problems and include:
	- Kodi version (git sha as long as we´re on agile only)
	- Inputstream.adaptive version (git sha as long as we´re on the agile branch)
	- Your OS and OS version
	- Libwedevine version
	- A Kodi debug log that represents your issue
	
###Licence
-----------------	

Licenced under The MIT License.
Includes [pyjsparser](https://github.com/PiotrDabkowski/pyjsparser) by [Piotr Dabkowski](https://github.com/PiotrDabkowski)
