# Spirit Lake Magic for FS3

## Credit
This plugin by Tat @ Ares Central.

## Overview

This is a sprawling plugin that brings magic to Faraday's FS3 system. Features include:

- Schools of magic
- Magic spells
- Magic items
- Potions

Each of these features is complex, and I highly suggest reading the documentation on each before deciding whether this plugin suits your needs.

### Magic and FS3

This is a magic system built around FS3, which means there are some limitations. Spells work within the framework of combat. This means that you can mod someone's initiative, attack, or defense, but not their strength. It means that damage is applied via the FS3 damage system, and healed the same way.

If you're considering using this system, know that you'll need to work WITH FS3, not against it. This will work best with custom magic systems rather than trying to fit existing systems into its framework - although creativity can often get you a long way.

### Coding Needs

**WARNING**
This is NOT a plug-and-play plugin.

Using this plugin will require a coder who is comfortable with altering core Ares code. I have tried to keep the intrusions to a minimum, and much of the day-to-day work is done in yml configuration files, but there are inevitably pieces that must be inserted into the FS3 code.

A coder doesn't need to be able to do much more than cut and paste and troubleshoot configuration errors, but those two things DO require some skill, some fearlessness, or possibly both. It is my hope that this plugin can make a complex magic system available to new or casual coders who are willing to experiment, but may not have the time or know-how to code a system from scratch.

I **strongly** suggest using github to back up your code and adding your configuration files. 

Additionally, while this code has been play-tested extensively on Spirit Lake from 2018-2021, there are almost certainly pieces which will break when taken into a new environment. I will do my best to provide support to the first few games to use this code in an effort to smooth out any lingering bugs. You should plan to set it up in a development server and test it thoroughly well before your game goes live.

## Installation
In the game, run `plugin/install <github url>`.

In addition, there are several places where code should be inserted into the FS3 core code by hand. I suggest inserting both the required and optional code, but in theory skipping the optional code won't actually break anything.

- Required FS3 Code
- Optional FS3 Code

## Configuring

- Overall Magic Configuration
- Spell Configuration
- Special FS3 Configuration

## Uninstalling

Removing the plugin requires some code fiddling.  See [Uninstalling Plugins](https://www.aresmush.com/tutorials/code/extras.html#uninstalling-plugins).


## License
This plug-in includes a variety of example spells and weapons. These are EXAMPLES ONLY and should not be used in your live game.

Same as [AresMUSH](https://aresmush.com/license).
