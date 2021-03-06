# titles

Lets you choose from a variety of titles to use for your character client-side only, whether you have unlocked the corresponding achievements or not.
Supports UI functionality with the optional ui mod below and auto update when using Caali's proxy.

### Prequisites

* [command](https://github.com/pinkipi/command) - by Pinkie Pie
* [ui](https://github.com/pinkipi/ui) - by Pinkie Pie (Optional)

### Usage

* `/proxy title` or `/8 title` to show the ingame title select window. (Only works with the ui mod as mentioned above)
* `/proxy title [achievement id]` or `/8 title [achievement id]` to instantly switch to the title related to the specific achievement id. (Achievement ID argument is required if the UI module is missing)

### Additional Information

* Your titles for every character are being saved client side in a file called `player.json` and are loaded each time you log in to each one.
* The available titles to use are included in `titles.json` which has been parsed from the EU client datacenter. Some titles may be unavailable to use on other regions.
* Some titles may appear multiple times and others may not work correctly, or not work at all.