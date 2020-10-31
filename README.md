# BashJect
Bash script to mimic JECT functionality for the Linux Creatures Evolution Engine

# Disclaimers
Use at your own risk and save your world first. This seems to work fine for small and simpler cosfiles but **breaks and crashes your game when the scripts are too big and for other random reasons I don't know yet.** There's still a lot of work to do on this. No telling if I'll ever get it into a more stable state.

This is my first time doing anything remotely complicated in Bash and I barely have any clue what I'm doing. Please send PRs if you know better. This is a product of my own stubbornness and probably should have been done in anything other than Bash, but here we are.

# Usage
Intended to work simliar to the JECT CAOS command. Stick it in a folder and run something like `./ject path/to/cosfile.cos 2`. It's nicer if you add it to your path.

The flags paramter is the same as the equivalent [CAOS command](https://creatures.wiki/JECT): 1-- Remove Script, 2-- Event Script(s), 4-- Install Script.

You can leave it out and it'll assume 7 (full reinstall of the cosfile)

# Script Status

Provided for narrowing down problems in the future:

## Vanilla DS Cosfiles That Seem To Inject Fine
* arch.cos
* babel_fast_info.cos
* C3_grendel_rainmaker.cos
* c3_incubator_recreator.cos

## Vanilla DS Cosfiles That Cause Errors But Don't Crash
* agent injector.cos
* capillata umbilical.cos

## Vanilla DS Scripts That Crash The Game When Injected
* autorecovery.cos
* babel_connection_information.cos*
* bramboo.cos
* C3_airlock_scripts.cos
* C3_creator.cos
* carrot pod.cos*
* chat - chat module.cos
* chat - chat request indicator.cos
* chat - chat scripts.cos
* chat - in chat invitation manager.cos
* chat - the interpreters.cos**
* commedia.cos
* comms camera screens.cos
* comms camera units.cos**
* comms screen.cos
* contact book.cos

\*Throws a specific error "pos2 > len2" before crashing instead of segfaulting

\*\*Throws a slightly different segfault?

## Untested Vanilla DS Scripts
* 'contact buttons.cos'
* 'containment chamber.cos'
* 'creature care kit scripts.cos'
* creature_warning.cos
* 'dev tool.cos'
* doors.cos
* 'DS agent help.cos'
* 'DS autosave.cos'
* 'DS bacteria.cos'
* 'DS Blueprint Agent Export As Pray File.cos'
* 'DS blueprint agent scripts.cos'
* 'DS CAOS command line.cos'
* 'DS connecting agent pointer change.cos'
* 'DS creatureBreeding.cos'
* 'DS creatureBubbles.cos'
* 'DS creatureDecisions.cos'
* 'DS creatureDoneTo.cos'
* 'DS creature history.cos'
* 'DS creatureInvoluntary.cos'
* 'DS creatureObjectVariables.cos'
* 'DS creaturesAffectingHand.cos'
* 'DS creatureToCreature.cos'
* 'DS death.cos'
* 'DS disable debug keys.cos'
* 'DS Frame rater.cos'
* '!DS_game variables.cos'
* 'ds gui - creaturemenu.cos'
* 'ds gui - inventory.cos'
* 'ds gui - options.cos'
* 'ds gui - topleft.cos'
* 'DS HoldingHandsControlScripts.cos'
* 'DS Home smell emitters.cos'
* 'DS keyboard handler.cos'
* 'DS life event factory - PHOTOGRAPHS THE DEAD.cos'
* 'DS magic profiler.cos'
* 'DS norn indicator.cos'
* 'DS object of attention indicator.cos'
* 'DS pointer activate stimming norns.cos'
* 'DS pointer.cos'
* 'DS Pointer scripts.cos'
* 'DS scroll settings.cos'
* 'DS speech bubble factory.cos'
* 'DS textentry.cos'
* 'DS welcome screen.cos'
* 'DS wolf control.cos'
* 'empathic vendor.cos'
* explodonut.cos
* 'heatpan incubator.cos'
* 'holistic learning machine.cos'
* hoverdoc.cos
* 'immigrant checker.cos'
* 'justanut pod.cos'
* 'keycode displayer.cos'
* '!kill duplicate Creatures 3 agents.cos'
* 'lemon pod.cos'
* 'lift ca linkers.cos'
* lift_cutaway.cos
* '!map.cos'
* '!meso environment.cos'
* 'message centre.cos'
* 'mini empathic vendor.cos'
* musicola.cos
* 'nav lift.cos'
* new_ds_fav_places.cos
* 'new keyboard handler.cos'
* 'NEW portal dispensor.cos'
* 'NEW portals.cos'
* 'Norn Egg layer.cos'
* 'portable teleporter.cos'
* 'power to the shee starship.cos'
* 'random user contact.cos'
* 'robot toy.cos'
* snotrock.cos
* 'stinger pod.cos'
* 'system notification.cos'
* tooltips.cos
* 'training dummy.cos'
* trapper.cos
* tuba.cos
* 'warning icons.cos'
* waterspouts.cos
* 'workshop liftmask.cos'
* 'workshop screen.cos'
* '!world_tints.cos'
* 'z_DS agent smells.cos'
* 'z_DS creaturesAffectingAnimals.cos'
* 'zz mesa light and heat.cos'
* zzz_click_to_go_online.cos
* zzz_gamestart_login.cos
* zzzy_CheckCreatureDropScript.cos
* zzzz_CreatureHasBeenDropped.cos
