# BashJect
Bash script to mimic JECT functionality for the Linux Creatures Evolution Engine

# Disclaimers
Use at your own risk and save your world first. This seems to work fine for small and simpler cosfiles but **breaks and crashes your game when the scripts are too big and for other random reasons I don't know yet.** There's still a lot of work to do on this. No telling if I'll ever get it into a more stable state.

This is my first time doing anything remotely complicated in Bash and I barely have any clue what I'm doing. Please send PRs if you know better. This is a product of my own stubbornness and probably should have been done in anything other than Bash, but here we are.

# Usage
Intended to work simliar to the JECT CAOS command. Stick it in a folder and run something like `./ject path/to/cosfile.cos 2`. It's nicer if you add it to your path.

The flags paramter is the same as the equivalent [CAOS command](https://creatures.wiki/JECT): 1-- Remove Script, 2-- Event Script(s), 4-- Install Script.

You can leave it out and it'll assume 7 (full reinstall of the cosfile)
