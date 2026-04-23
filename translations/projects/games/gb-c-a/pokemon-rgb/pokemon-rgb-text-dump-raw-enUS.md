---
aliases:
  - Pokémon Red Game Script
  - Pokémon Blue Game Script
  - Pokémon Green Game Script
  - Pokémon Yellow Game Script
source: https://gamefaqs.gamespot.com/gameboy/367023-pokemon-red-version/faqs/48982
Origin Date: 2007-06-25
---

# Pokémon Generation 1 Game Script

> [!cite]+ Source Information
Author    : mtkennerly (formerly known as TheSinnerChrono)
Email     : mtkennerly+faq@gmail.com
Version   : v03
Created   : 2007-06-25
Updated   : 2024-07-29
Project # : 15
Profile   : https://www.gamefaqs.com/community/mtkennerly/contributions

> [!note]+ Note 1
> To skip to a particular section, initiate the search function in the program with which this file is being viewed, and input the [] code that precedes the desired portion's name in the table of contents. Include the brackets to ensure the propriety of the result.

> [!note]+ Note 2
> As per Gold/Silver/Crystal, the player's character is named Red, and the rival thereof is named Blue.

## Table of Contents \[00'00]

- Section 01
	- \[01'00] Additional Notes
	- \[01'01] Format
	- \[01'02] Versions
	- \[01'03] Legal
- Section 02
	- \[02'00] Script (Red/Blue)
	- \[02'01] Pallet Town
	- \[02'02] Route 1
	- \[02'03] Viridian City
	- \[02'04] Route 2 & Viridian Forest
	- \[02'05] Pewter City
	- \[02'06] Route 3
	- \[02'07] Mt. Moon
	- \[02'08] Route 4
	- \[02'09] Cerulean City
	- \[02'10] Route 24
	- \[02'11] Route 25
	- \[02'12] Route 5
	- \[02'13] Route 6
	- \[02'14] Vermilion City
	- \[02'15] Diglett's Cave & Route 2
	- \[02'16] Route 9
	- \[02'17] Route 10 & Rock Tunnel
	- \[02'18] Lavender Town
	- \[02'19] Route 8
	- \[02'20] Celadon City
	 - \[02'21] Lavender Town
	 - \[02'22] Saffron City
	 - \[02'23] Route 11
	 - \[02'24] Route 12
	 - \[02'25] Route 13
	 - \[02'26] Route 14
	 - \[02'27] Route 15
	 - \[02'28] Route 16
	 - \[02'29] Route 17
	 - \[02'30] Route 18
	 - \[02'31] Fuchsia City
	 - \[02'32] Sea Route 19
	 - \[02'33] Sea Route 20
	 - \[02'34] Cinnabar Island
	 - \[02'35] Sea Route 21
	 - \[02'36] Viridian City
	 - \[02'37] Route 22
	 - \[02'38] Route 23
	 - \[02'39] Victory Road
	 - \[02'40] Indigo Plateau
- ## 03
	- \[03'00] Addenda
	- \[03'01] Recurrent Script
	- \[03'02] Pokemon Yellow
	- \[03'03] Pokedex

## Comments & Notes

### Additional Notes \[01'00]

_There are no additional notes._

### Format \[01'01]

> [!quote] Object
> 
Citation of objects in speaker identification (\[!quote] callout) denotes that the proceeding text is that of the message displayed upon examination of the objects in question.

* - Text

Descriptions of character actions, et cetera.

   -(Text)

Following the above would be the events prompted by a particular option.
The number of hyphens corresponds to the choice layer; i.e., the first set
of options will have one hyphen, the second set will have two, and so on.
One equal sign accounts for two hyphens.


```
#$#$#$#$#$#$#$#$#$#$#$#$
$#  Pokemon trainers  #$
#$#$#$#$#$#$#$#$#$#$#$#$
```

Parts of script for trainers whom one can engage in battle are identified thus:

"{Start}"  =  Start of trainer encounter
"{Class}"  =  Classification (Bug catcher, swimmer, et cetera)
"{End}"  =  End of battle
"{After}"  =  After having defeated the trainer, when speaking to him/her again


```
#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#
#$#$#$#$#$#$#$                               $#$#$#$#$#$#$#
#$# [01'02] ---           Versions          --- [01'02] #$#
#$#$#$#$#$#$#$                               $#$#$#$#$#$#$#
#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#
```

   [ v01  -  2007-06-25 ]
* Initial release.


   [ v02  -  2007-07-26 ]
* Added "Recurrent Script" section.


   [ v03  -  2024-07-29 ]
* Updated contact information.
* Added legal section.


```
#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#
#$#$#$#$#$#$#$                               $#$#$#$#$#$#$#
#$# [01'03] ---             Legal           --- [01'03] #$#
#$#$#$#$#$#$#$                               $#$#$#$#$#$#$#
#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#
```

This document is released under CC-BY-SA 4.0:
https://creativecommons.org/licenses/by-sa/4.0

This does not apply to the game's verbatim dialogue or characters,
which I do not own. This document is intended to encourage and assist
discussions of the game and its story.

## Script for Red & Blue Version \[02'00]

[2.01 - Pallet Town](translations/projects/games/gb-c-a/pokemon-rgb/script/2.01%20-%20Pallet%20Town.md)