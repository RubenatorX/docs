---
permalink: /addons/cellhelp/
title: CellHelp
---

**Authors:** Balloon, Krizz<br>
**Version:** 2.0<br>
**Date:** 20130429

Cell Helper, for old Salvage

**Abbreviation:** `//ch`

## Commands

### help
```
ch help
```

Shows a menu of commands in game

### position
```
ch pos <x> <y>
```

Positions the Lot Order box. Default location is 1000,250.

### hide
```
ch hide
```

Hides the Lot Order box

### show
```
ch show
```

Shows the Lot Order box

### set
```
ch set [set id]
```

Loads set from settings file. Default is set1.

### mode
```
ch mode [lots/nolots]
```

If set to nolots, ll will not lot cells. Default is lots.

### timer
```
ch timer [start/stop]
```

Will start or stop the 100 minute zone timer.

## Other Information
* If you need to remove a cell from the Lot Order box, type in `/echo [You] obtains a --[cellname] cell--.` You must have the dashes around the cellname, and the period at the end.
* If you have gear you want to pass or lot, add it in the appropriate tags for your player. If not, leave the value as **0**. Otherwise you will see errors.
* As with the base LL, items already in the pool cannot be lotted/passed when the profile is loaded.


## To Do
* Support for more than 4 people
* Remove (or create a toggle) for the Item Counter.
* Enable xml creation if settings file is not found.
* Change zone comparison to use zone IDs.
* Ability to add cell back to list.
* Box parameter settings.
* Interface adjustments. Icons?

## Known Issues
* Pass tag errors
* Cellhelp shows itself again after hide.

## Source
The latest source and information for this addon can be found on [GitHub](https://github.com/Windower/Lua/tree/live/addons/cellhelp).