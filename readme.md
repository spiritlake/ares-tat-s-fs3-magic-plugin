# Tat's FS3 Magic

**This plugin is NOT publicly released and is still being formatted correctly. Do not attempt to use!**

## Credit
This plugin by Tat @ Ares Central.

## Overview

This is a sprawling plugin that brings magic to Faraday's FS3 system. Features include:

- [Schools of magic](https://github.com/spiritlake/ares-tat-s-fs3-magic-plugin/wiki/Schools)
- [Magic spells](https://github.com/spiritlake/ares-tat-s-fs3-magic-plugin/wiki/Spells#spell-effects)
- [Magic items](https://github.com/spiritlake/ares-tat-s-fs3-magic-plugin/wiki/Magic-Items)
- [Potions](https://github.com/spiritlake/ares-tat-s-fs3-magic-plugin/wiki/Potions)

Each of these features is complex, and I highly suggest reading the [overview and documentation](https://github.com/spiritlake/ares-sl-magic-for-fs3-plugin/wiki) on each before deciding whether this plugin suits your needs. 

### Magic and FS3

This is a magic system built around FS3, which means there are some limitations. Most spells work within the framework of combat. This means that you can mod someone's initiative, attack, or defense, but not their strength. It means that damage is applied via the FS3 damage system, and healed the same way.

If you're considering using this system, know that you'll need to work WITH FS3, not against it. This will work best with custom magic systems rather than trying to fit existing systems into its framework - although creativity can often get you a long way.

### Coding Needs

**WARNING**

**This is NOT a plug-and-play plugin.**

Using this plugin will require a coder who is comfortable with altering core Ares code. I have tried to keep the intrusions to a minimum, and much of the day-to-day work is done in yml configuration files, but there are inevitably pieces that must be inserted into the FS3 code.

A coder doesn't need to be able to do much more than cut and paste and troubleshoot configuration errors, but those two things DO require some skill, some fearlessness, or possibly both. It is my hope that this plugin can make a complex magic system available to new or casual coders who are willing to experiment, but may not have the time or know-how to code a system from scratch. It is unfortunately NOT going to make it available to folks who are entirely uncomfortable adjusting and troubleshooting code.

I **strongly** suggest using github to back up your code and adding your configuration files.

Additionally, while this code has been play-tested extensively on Spirit Lake from 2018-2022, there are almost certainly pieces which will break when taken into a new environment. You should plan to set it up in a development server and test it thoroughly well before your game goes live.

## Installation
In the game, run `plugin/install <github url>`.

In addition, there are several places where code should be inserted into the FS3 core code by hand. I suggest inserting both the required and optional code, but in theory skipping the optional code won't actually break anything.

- [Required FS3 Code](https://github.com/spiritlake/ares-sl-magic-for-fs3-plugin/wiki/Required-FS3-Code)
- [Optional FS3 Code](https://github.com/spiritlake/ares-sl-magic-for-fs3-plugin/wiki/Optional-FS3-Code)
- [Optional Web Portal Code](https://github.com/spiritlake/ares-sl-magic-for-fs3-plugin/wiki/Optional-Web-Portal-Code)

## Configuring

- [General Configuration](https://github.com/spiritlake/ares-tat-s-fs3-magic-plugin/wiki/General-Configuration)
- [Spell Configuration](https://github.com/spiritlake/ares-tat-s-fs3-magic-plugin/wiki/Configuring-Spells)
- [Special FS3 Configuration](https://github.com/spiritlake/ares-tat-s-fs3-magic-plugin/wiki/FS3-Special-Configuration)

## Uninstalling

Removing the plugin requires some code fiddling.  See [Uninstalling Plugins](https://www.aresmush.com/tutorials/code/extras.html#uninstalling-plugins).


## License
This plug-in includes a variety of example spells and weapons. These are EXAMPLES ONLY and should not be used in your live game.

Same as [AresMUSH](https://aresmush.com/license).
