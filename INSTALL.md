# Linux

	sudo apt-get install git python

	git clone https://github.com/futurefractal/g1utils
	cd g1utils

# Mac

In **Terminal**, run:

	xcode-select --install

	git clone https://github.com/futurefractal/g1utils
	cd g1utils

# Windows

To build on Windows, use [**Cygwin**](http://cygwin.com/install.html). Use the default settings in the installer.

In the installer, select the following packages: `git` `python`

In the **Cygwin terminal**:

	git clone https://github.com/futurefractal/g1utils
	cd g1utils

 # Running the script

 Once you have cd'd into the folder depending on where you installed the script now you may run this command:

 `python g1dump.py <rom path> <command>`

 Here are a list of commands to use:

 `mon <num>`: Display complete info about the Pokémon with the given index number
 
 `mon-family <num>`: Display complete info about the given Pokédex number
 
 `move <num>`: Display info about the given move
 
 `map-info <num>`: Display info about the given map
 
 `all-glitchmons`: Display info about all glitchmons
 
 `all-glitchmon-families`: Display info about all glitch Pokédex numbers
 
 `all-unused-glitchmon-families`: Display info about all unused glitch Pokédex numbers
 
 `all-glitch-moves`: Display info about all glitch moves
 
 `all-glitch-types`: Display the names of all glitch types
 
 `all-used-glitch-trainers`: Display info about all accessible glitch trainers
 
 `all-used-glitchmon-palettes`: Display all glitch palettes used by glitchmons
 
 `all-glitch-exp-groups`: Display info about all glitch experience groups
 
 `all-used-glitch-exp-groups`: Display info about all glitch experience groups used by glitchmons
 
 `all-glitchmon-cries`: Display info about all glitchmons' cries
 
 `all-glitch-items`: Display info about all glitch items

 `map <png-path> <num> [colortype]`: Export a PNG file of the map with the given index number
 
 `displaced-map <png-path> <num> <block-address> <x> <y> [colortype]`: Export a PNG file of a glitched map.
 
 `glitchcity <png-path> <num> <door-id> [colortype]`: Export a PNG file of a wrong-warp glitch city (Door ID 4 for the classic Safari Zone method)
 
 `mon-sprite <png-path> <num> [colortype]`: (Alias for mon-frontsprite)
 
 `mon-frontsprite <png-path> <num> [colortype]`: Export a PNG file of the frontsprite of the Pokémon with the given index number
 
 `mon-backsprite <png-path> <num> [colortype]`: Export a PNG file of the backsprite of the Pokémon with the given index number
 
 `mon-family-sprite <png-path> <num> [colortype]`: (Alias for mon-family-frontsprite)
 
 `mon-family-frontsprite <png-path> <num> [colortype]`: Export a PNG file of the frontsprite of the given Pokédex number
 
 `mon-family-backsprite <png-path> <num> [colortype]`: Export a PNG file of the backsprite of the given Pokédex number
 
 `trainer-sprite <png-path> <num> [colortype]`: Export a PNG file of the sprite for the given trainer ID
 
 `tileset-gfx <png-path> <num>`: Export a PNG file of the graphics for the given tileset ID
 
 `tileset-blocks <folder-path> <num>`: Export PNG files for each block in the given tileset ID


