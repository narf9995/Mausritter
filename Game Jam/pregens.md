# Millions of Mice
The Mausritter rulebook explicitly states the intent for players to act brave, kill off mice often, & reroll new ones.
The character creation process is very quick already, but it could be made quicker by automation via computers.
But with "millions of mice" comes storage issues, so a new shorthand called the Quick Mouse Identifier (QMI) is proposed in this supplement.

## Quick Mouse Identifier (QMI)
A QMI is a 5 digit pseudo-hexadecimal string that summarizes an entire *Mausritter* character.
It isn't meant to replace character sheets, instead it is a way to quickly reference a character's stats without needing their full statblock.

To simplify, hexadecimal is used by computers to make 2 digit numbers fit in the space of 1 digit.

The string is in the order: STR, DEX, WIL, HP, & Pips. 

> For example, B9C31 would be read as:
> 
> STR: 11, DEX: 9, WIL: 12, HP: 3, & Pips: 1.

This obviously doesn't account for other things like backgrounds, items, spells, etc. so here's an example of how one might implement QMI as part of a full character sheet:
> [Name] ([QMI])
>
> [Background]
> 
> Items: [Main], [Off], [Worn 1], [Worn 2], [Pack Items 1-6]

### Pseudo-Hexadecimal
Decimal | Hexadecimal
:---: | :---:
10 | A
11 | B
12 | C
13 | D
14 | E
15 | F
16 | G
... | ...
35 | Z


## Mass Character Gen
Characters can easily be created en masse using the dice program Troll, which can be found online at the URL: [https://topps.diku.dk/torbenm/troll.msp](https://topps.diku.dk/torbenm/troll.msp)

1. Navigate to & select the Mausritter Character in the "user-contributed roll" list (or just type in the code below).
2. Set "Number of rolls" to the number of characters you wish to create.
3. Press "Make random rolls" button & navigate to the bottom of the page.

``` 
\ Mausritter Character

"STR |>DEX |>WIL |>HP |>Pips" || 3'sum largest 2 3d6 <| 2'sum 1d6
``` 


## But Why?
Here's an example as to why one would go through all this effort.

Below are 5 mice in standard format & the same 5 mice, but in QMI format.


### Standard
- STR: 11, DEX: 9, WIL: 9, HP: 3, Pips: 1
- STR: 7, DEX: 11, WIL: 5, HP: 2, Pips: 4
- STR: 10, DEX: 9, WIL: 11, HP: 1, Pips: 3
- STR: 9, DEX: 9, WIL: 7, HP: 6, Pips: 5
- STR: 3, DEX: 8, WIL: 11, HP: 5, Pips: 6

### QMI
- B9931, 7B524, A9B13, 99765, 38B56

### The answer
The issue is magnified by the number of characters resulting in issues with space & readability.
This matters less when you have 5 mice, but what about 100 or 1,000?
Or even 1,000,000?

That might sound insane for a fantasy game, but some sci-fi games that involve intergalactic travel such as *Traveler* regularly generate entire galaxies.
The hexadecimal idea was actually taken from *Cepheus Engine*, a modern *Traveler* clone, which also does it for entire planets & galaxies.

Just 10 mice on 10 planets is already 100 mice.
Multiply that by the number of galaxies & things start to get crazy... or maybe your GM just wants to run *Tomb of Horrors*, but with mice.
Either way, this is a solution to problem you probably didn't have, but hopefully it's still useful in your game.

## 100 Mice
To make reading this worth your time, here's 100 fresh mice in QMI format made with Troll as outlined above:

- BB913, 4BB35, 9B862, 3C911, 7AA12
- B8B21, 45B12, 97B33, C9464, 6A942
- 8A832, BC412, 69A62, B9C54, C4515
- C8434, 9A916, 9BB65, 89763, 65A33
- 7A955, 7AA21, 96843, 99831, 8AA54
- 9BA34, 56966, B4961, BA951, 96714
- 6AB41, 87713, C7B64, B8546, CBA25
- C8A64, 78852, 68911, 3B546, 98713
- 5A611, B6C45, 4A964, 8B936, 97634
- 7CA13, C9C41, 86926, 8BB51, A8A42
- 97C65, 97A36, A9434, 35951, 9A421
- B8762, BA956, 8A841, 66822, CA814
- 97813, 98425, 78944, 97B36, 8A864
- 88A36, A8762, C5C65, 7A726, 54514
- AC631, A7C42, 98A25, ACB22, 89A14
- 38C43, 97956, A9B51, 5B956, 76633
- 6A844, 7C821, 88C11, B6A13, 9B654
- 9B961, 64A51, 95724, 99633, 45866
- 89C56, 49C12, 8CC64, 69B61, 87751
- 75A65, C6612, 7AA45, CA726, 86946

> These should be more than enough fodder for your home game, but if your table is extremely lethal, then rest assured, as I'll soon attempt to make an additional supplement that legitimately contains 1,000,000 mice in QMI format.
> 
> Don't spend them all in one place. ;)
