# MinecraftInstance Tools
> Tools for manipulating Twitch's minecraftinstance.json file

## Motivation
This project provides you with all the tools needed to manage Twitch's `minecraftinstance.json` quickly, efficiently, and in a version control (diff) friendly way.

## Tools
- ### [Addon remover](remover.py)
  - Search for addons
  - Remove addons
  - Remove addons' dependencies if not used by other addons

- ### [Addon differ](differ.py)
  - Diff two versions of `minecraftinstance.json`
  - Produce a new instance file with the minimum amount of changes to achieve the second version's state from the first one
