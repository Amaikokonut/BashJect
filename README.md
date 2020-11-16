# BashJect
Bash script to mimic JECT functionality for the Linux Creatures Evolution Engine

# Disclaimers
Use at your own risk and save your world first. Since the the script injection was rewritten this is a lot more stable and reliable, but you never know when you'll be the first to find something that explodes.

This is my first time doing anything remotely complicated in Bash and I barely have any clue what I'm doing. Please send PRs if you know better. This is a product of my own stubbornness and probably should have been done in anything other than Bash, but here we are.

# Usage
Intended to work simliar to the JECT CAOS command. Stick it in a folder and run something like `./ject path/to/cosfile.cos 2`. It's nicer if you add it to your path.

The flags paramter is the same as the equivalent [CAOS command](https://creatures.wiki/JECT): 1-- Remove Script, 2-- Event Script(s), 4-- Install Script.

You can leave it out and it'll assume 7 (full reinstall of the cosfile)

# Script Status

All vanilla DS cosfiles appear to inject cleanly and without issue.
