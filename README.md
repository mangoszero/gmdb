GMDB for MaNGOSZero / CMaNGOS Classic
==========

License
-------
**GMDB for MaNGOSZero / CMaNGOS Classic** is released under the Creative Commons Attribution-NonCommercial-ShareAlike 3.0.
The file (`LICENSE.md`) **must** be a part of any redistributable packages
made from this software.  No licenses should be removed from this software if
you are making redistributable copies.

How to Install MANGOSZero
-------
Short instruction:

1. enter _tools directory

2. run: make_full_db.bat (if you are doing it under Windows) or run: /bin/sh make_full_db.sh (if you are running
   it under *nix/Linux)

3. apply created file to mangos database, eg.: mysql -u root -p mangos < locales_mangos.sql

4. apply created file to scriptdev2 database, eg.: mysql -u root -p mangos < locales_scriptdev2.sql

That's all!

How to Install CMaNGOS Classic
-------
Short instruction:

1. enter _cmangos directory

2. apply created files to mangos database:
mysql -u root -p mangos < locales_CMaNGOS_Classic.sql
mysql -u root -p mangos < creature_ai_texts_CMaNGOS_Classic.sql (optional)

3. apply created file to scriptdev2 database, eg.: mysql -u root -p scriptdev2 < script_texts_ScriptDev2.sql

4. enter _cmangos/updates directory and apply the created update files

That's all!
