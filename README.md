# Battle Talent - Base Projects

Hi and welcome. Above you will find a collection of some clean example projects to use for creating Battle Talent mods. Hope it helps!

## Important changes

Here are some tips to help you make beautifull mods.

### Prefixes

In the projects you will find a lot of `YOURPREFIX_` in names. You should change those to your own cool modder tag so your mods will not conflict with others.

### Code changes

Only actual CODE changes that are needed per project are the following:

Step 1 - Entry.txt
In `Setup\Scripts\Entry.txt` edit ```print("Loading YOURPREFIX_PROJECTNAME")``` 

Step 2 - Entry.txt
In `Setup\Scripts\WeaponModDemo.txt` edit ```AddStoreItemTemplate("YOURPREFIX_PROJECTNAME", nil, "Weapon name", "A description about the weapon.")``` 

### Icon changes

ALWAYS test if the mod shows up correctly in the store.
