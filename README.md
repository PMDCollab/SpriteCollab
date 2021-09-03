**Key**
* :star: Fully Featured: Contains all emotions in high quality.
* :white_check_mark: Exists: Contains at least a Normal emotion in high quality.
* :white_circle: Incomplete: Contains at least a Normal emotion, but considered unfinished.
* :x: Missing
* :black_circle: Not Needed
* :grey_question: Pending Submission
* :interrobang: Finished, with Pending Revision



**MAIN WEBSITE**
http://sprites.pmdcollab.org/



**REPOSITORY**
https://github.com/PMDCollab/SpriteCollab



**HOW TO SUBMIT PORTRAITS**
1. Download the template for the Pokemon you want to submit or recolor, using `!portrait`, or `!recolorportrait`.
2. Paste in the portraits in the correct places and save the file without changing its name.
  -Portraits must be 40x40 in size. Try to keep them within 15 colors.
  -Do not replace chunsoft-made portraits and emotions in your submissions.  Try to refrain from replacing them in general, unless the portrait is marked as incomplete.
3. Re-upload the file directly to the #submissions channel and await approval.

**HOW TO SUBMIT SPRITES**
1. Download the template for the Pokemon you want to submit or recolor, using `!sprite`, or `!recolorsprite`.
2. Add the animations and XML data to the zipped folder.  Consult a full guide here: https://docs.google.com/document/d/1EceEEjyeoFwoKXdNj4vpXdoYRWp8CID64e-ZqY954_Q
3. Re-upload the file directly to the #submissions channel and await approval.  It must be zipped with the same name as you got it.

Note: By submitting files to the bot, you provide permission for others to use, copy, redistribute, or modify said files for their own projects and contributions, so long as credit to the original artist is retained.  For more info view the license on the repository.


**POLICY ON OFFICIAL SPRITES**
As a rule, we do not allow modifications or overwriting of any existing Chunsoft portraits or sprites within the SpriteBot repository (with the exception of shinies), nor do we allow unofficial Pokemon/unofficial forms of Pokemon to be added to the repository.

However, there are some special submission cases that warrant the creation of new sprite and portrait slots in order for them to be added to the repository:
* Alternate versions of existing emotion portraits/entire portrait sets and/or spritesheets that are deemed to be of a high enough quality standard to be accepted can be added in a new slot created for the relevant Pokemon that is labeled Alternate.
* Recolors of portraits and sprites that modify the existing Chunsoft color palettes to better match the canonical color palettes used for the Pokemon in the mainline game series can be added in a new slot created for the relevant Pokemon that is labeled AltColor.
* Portraits and sprites of Pokemon that were discovered in beta versions of mainline Pokemon games can be added in a new form slot of either Missingno. in the case of there being no applicable Pokemon that it is a prototype of, or in a new form slot of the Pokemon it is a prototype of that is labeled Beta.
* Portraits and sprites of alternate forms of Pokemon shown in official spin-off games (e.g. Shadow Lugia and similar cases) can be added in a new form slot created for the relevant Pokemon labeled with the official name of the form.

If a special use-case sprite or portrait does not fit into any of the above categories, it will not be accepted into the Sprite Repository.


**COMMANDS**
All commands are case-insensitive.
```
!portrait <Pokemon Name> [Pokemon Form] [Shiny] [Gender]
  !portrait Pikachu
  !portrait Shaymin Sky
  !portrait Pikachu Female
  !portrait Shaymin Sky Shiny
  !portrait Pikachu Shiny Female
Gets all portrait emotions for a pokemon in a single spritesheet.

!recolorportrait <Pokemon Name> [Pokemon Form] [Gender]
  !recolorportrait Pikachu
  !recolorportrait Shaymin Sky
  !recolorportrait Pikachu Female
Gets all portrait emotions for a pokemon in a single spritesheet, with a palette bar at the top to make recoloring easier. Fails if the original doesn't exist.

!sprite <Pokemon Name> [Pokemon Form] [Shiny] [Gender]
  !sprite Pikachu
  !sprite Shaymin Sky
  !sprite Pikachu Female
  !sprite Shaymin Sky Shiny
  !sprite Pikachu Shiny Female
Gets all spritesheets for a pokemon in a single zip file.

!recolorsprite <Pokemon Name> [Pokemon Form] [Gender]
  !recolorsprite Pikachu
  !recolorsprite Shaymin Sky
  !recolorsprite Pikachu Female
Gets all spritesheets for a pokemon, compressed in a single spritesheet, with a palette bar at the top to make recoloring easier. Fails if the original doesn't exist.
```


```
!register [Name] [Contact]
  !register
  !register Parakoopa
  !register Audinowho https://github.com/audinowho 
Sets your name and contact info for use in crediting you when distributing sprite packs. By default you are credited by discord ID.

!profile
  !profile
Shows your current name and contact info as used in credits.
```



**REVIEWER COMMANDS**
```
!add <Pokemon Name> [Pokemon Form]
  !add Calyrex
  !add Mr_Mime Galar
Adds a species, or a new form to an existing species. Auto-generates shiny slots.

!rename <Pokemon Name> [Pokemon Form] <New Name>
  !rename Calrex Calyrex
  !rename Vulpix Aloha Alola
Changes the existing species or form to the new name.

!delete <Pokemon Name> [Pokemon Form]
  !delete Pikablu
  !delete Arceus Mega
Removes a species or form. Only works if the slot its children are empty. Must be on the last slot in its list.

!addgender <Pokemon Name> [Pokemon Form] <Sprite|Portrait>
  !addgender Venusaur Sprite
  !addgender Steelix Portrait
  !addgender Raichu Alola Sprite
Adds a slot for the female version of the species, or form of the species.  Must specify "sprite" or "portrait" at the end.

!deletegender <Pokemon Name> [Pokemon Form] <Sprite|Portrait>
  !deletegender Venusaur Sprite
  !deletegender Steelix Portrait
  !deletegender Raichu Alola Sprite
Removes the slot for the female version of the species, or form of the species. Only works if empty.  Must specify "sprite" or "portrait" at the end.
```


```
!portraitexists <Pokemon Name> [Pokemon Form] [Shiny] [Gender]
  !portraitexists Pikachu
  !portraitexists Shaymin Sky Shiny
Marks a Pokemon portrait as "Exists". Portraits are considered "Incomplete" when accepted, and this status must be marked by reviewers when they meet quality standards.

!portraitfilled <Pokemon Name> [Pokemon Form] [Shiny] [Gender]
  !portraitfilled Pikachu
  !portraitfilled Shaymin Sky Shiny
Marks a Pokemon portrait as "Filled". This status must be marked by reviewers when all emotions meet quality standards.

!spriteexists <Pokemon Name> [Pokemon Form] [Shiny] [Gender]
  !spriteexists Pikachu
  !spriteexists Shaymin Sky Shiny
Marks a Pokemon sprite as "Exists". Sprites are considered "Incomplete" when accepted, and this status must be marked by reviewers when they meet quality standards.

!spritefilled <Pokemon Name> [Pokemon Form] [Shiny] [Gender]
  !spritefilled Pikachu
  !spritefilled Shaymin Sky Shiny
Marks a Pokemon sprite as "Filled". This status must be marked by reviewers when the sprite has the 13 basic animations, with shadows and offsets in the right place.
```


```
!portraitcredit <Pokemon Name> [Pokemon Form] [Shiny] [Gender]
  !portraitcredit Pikachu
  !portraitcredit Shaymin Sky Shiny
Gets the full list of contributors for a portrait, for use in crediting.

!spritecredit <Pokemon Name> [Pokemon Form] [Shiny] [Gender]
  !spritecredit Pikachu
  !spritecredit Shaymin Sky Shiny
Gets the full list of contributors for a sprite, for use in crediting.
```
