# aaa playground

# Installation
* Download and install nodejs https://nodejs.org/
* Install the dota2 addon manager
  * `npm i -g dota2-addon-manager`
* Initialize the addons directory using `d2am list` from inside your `dota 2 beta` directory.
* Check out this repository into `dota 2 beta/addons/`
* Create an empty addon using the dota2 tools called `aaa_playground`
* Run `d2am link` from inside the `dota 2 beta` directory
* Open the addon using the dota2 tools. Done!

## Building npc text files
To setup the dependencies run `npm install` from within `addons/aaa_playground/game/scripts`. You must also install the gulp cli, this is done with `npm i -g gulp-cli`. These steps only need to be done once.

To build the npc files from their sources, run `gulp` from within `addons/aaa_playground/game/scripts`.

# License
MIT
