# catbot
Discord bot for Pokemon Go users. It's written in python 3.6 and uses the discord.py library.

Currently, catbot has only one main purpose - to return Pokemon Go gym locations when given the name of the gym.

Give gyms are read in from a CSV file with the fields:
- name
- latitude
- longitude

Name matching is case, space, and punctuation insensitive and will do partial matches.

