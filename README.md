**Key**
:star: Fully Featured: Contains all emotions in high quality.
:white_check_mark: Exists: Contains at least a Normal emotion in high quality.
:white_circle: Incomplete: Contains at least a Normal emotion, but considered unfinished.
:x: Missing
:black_circle: Not Needed
:grey_question: Pending Submission
:interrobang: Finished, with Pending Revision

In the status list, the first column is Overworld Sprites, the second column is Portraits.


**MAIN WEBSITE**
http://sprites.pmdcollab.org/



**HOW TO SUBMIT PORTRAITS**
1. Download the template for the Pokemon you want to submit or recolor, using `!portrait`, or `!recolorportrait`.
2. Paste in the portraits in the correct places and save the file without changing its name.
  - Portraits must be 40x40 in size. Try to keep them within 15 colors.
  - Do not replace chunsoft-made portraits and emotions in your submissions.  Try to refrain from replacing them in general, unless the portrait is marked as incomplete.
3. Re-upload the file directly to the #submissions channel and await approval.

**HOW TO SUBMIT SPRITES**
1. Download the template for the Pokemon you want to submit or recolor, using `!sprite`, or `!recolorsprite`.
2. Add the animations and XML data to the zipped folder.  Consult a full guide here: https://docs.google.com/document/d/1EceEEjyeoFwoKXdNj4vpXdoYRWp8CID64e-ZqY954_Q
3. Re-upload the file directly to the #submissions channel and await approval.  It must be zipped with the same name as you got it.

**SUBMISSION AND USE POLICY**

By submitting files to the bot, you provide permission for others to copy and redistribute the material in any medium or format, or remix, transform, and build upon the material, as long as the work is `non-commercial` and `appropriate credit` is given. For specific terms, view the CC BY-NC license: https://creativecommons.org/licenses/by-nc/4.0/


**POLICY ON OFFICIAL SPRITES**

As a rule, we do not allow modifications or overwriting of any existing Chunsoft portraits or sprites within the SpriteBot repository (with the exception of shinies), nor do we allow unofficial Pokemon/unofficial forms of Pokemon to be added to the repository.

However, there are some special submission cases that warrant the creation of new sprite and portrait slots in order for them to be added to the repository:
- Alternate versions of existing emotion portraits/entire portrait sets and/or spritesheets that are deemed to be of a high enough quality standard to be accepted can be added in a new slot created for the relevant Pokemon that is labeled Alternate.
- Recolors of portraits and sprites that modify the existing Chunsoft color palettes to better match the canonical color palettes used for the Pokemon in the mainline game series can be added in a new slot created for the relevant Pokemon that is labeled AltColor.
- Portraits and sprites of Pokemon that were discovered in beta versions of mainline Pokemon games can be added in a new form slot of either Missingno. in the case of there being no applicable Pokemon that it is a prototype of, or in a new form slot of the Pokemon it is a prototype of that is labeled Beta.
- Portraits and sprites of alternate forms of Pokemon shown in official spin-off games (e.g. Shadow Lugia and similar cases) can be added in a new form slot created for the relevant Pokemon labeled with the official name of the form.

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

!help
  !help
  !help sprite
  !help recolorsprite
Shows info on available commands and specific commands.
```


**SUBMISSION FLAGS**

Add these to the post of your submission if you need them.
```
--author <Ping of Author>
  --author @Audino
  --author FELIS_LICHT
Lets you submit a sprite/portrait with credit to someone else. Also works on absentee profiles.

--base <Pokemon Name> [Pokemon Form] [Gender]
  --base Pikachu
  --base Shaymin Sky
  --base Pikachu Female
Allows you to submit recolor sheets as an entirely new Pokemon, based on the old Pokemon provided in the arguments. This uses the old Pokemon's animations, shadows, etc.
```
