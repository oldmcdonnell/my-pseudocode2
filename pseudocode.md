
# Object - Check

![Check](/IMG/check.jpg)

# Object - Trail Mark

![Trail Mark](/IMG/trailmark.jpg)

# Object - Harrow (hare's arrow)

![Harrow](/IMG/harrow.jpg)

# Object - Beer Near

![Beer Near](/IMG/beernear.jpg)

# Object - Song Check

![Song Check](/IMG/songcheck2.jpg)

# Object - Turkey Eagle split

![Turkey Eagle split](/IMG/turkeyeagle.jpg)

**function haresAway**
    -wait 10 minutes why Hares start the trail

**function searchForMark**  
```javascript
if (trailMark > 3) {
    continue searching
} else {
    blowWhistle, you are on trueTrail
}
```

While searchForMark if markFound relay information to the pack; 
- Shout "On 1" for one mark
- Shout "On 2" for two marks
- blowWhistle for three marks
- If another hasher asks "R U?" respond with the number of marks accordingly


**function blowWhistle**  
```javascript
If (you brought your whistle) { 
        blowYourWhistle 
    } else {
        shout "ON-ON"
    }
```
    print("congrats you are on trail")

**function songCheck**
1) From [Library](https://chicagohash.org/hashing-tools/hash-song-book/down-down-songs/) Array select random song
2) Put fist on head and sing "me me me me me"
3) Wait for acknowledge response "you you you you you"
4) Lead pack in song

**function beerNear**

    (possibility of being discovered by non-hasher = the creativity of the hiding spot)

    search for beer

**function turkeyEagle**

    - Turkey trails are happy shorter and fun
    - Eagle trails are longer, more dangerous, often wetter
    - Choose at your own peril

**function catchTheHare**
    - In the rare occurance of seeing the hare on trail yell "Hare spoted"
    - The hounds mush catch the hare before they get to ON IN
    - Punishment/reward depends on Kennel

# Hash Start
(before Hash Start hasherAge >= 21)

1) If liveHare Start haresAway, else goto 2
2) Init searchForMark, after 3 marks in a row you are on trail, blowWhistle, you are on trueTrail, continue in that direction.
3) If you are lost go back to the last mark and also listen for a whistle.
4) If you see another Hasher searchForMark shout "R U?" They will tell you how many marks they have found since the last check. 
5) If you hear a whistle, run in that direction.
6) If a check is found, init searchForMark again, when trail is found mark check with the correct direction with chalk for the walkers.
7) If a song check is found init songCheck - sing a song.
8) If harrow is found congrats you are on the correct trail, follow the harrow. 
9) If you see Beer Near, init beerNear, search for beer, function songCheck may also apply spontaneosly during beerNear.
10) If you see a Turkey Eagle split, init turkeyEagle, choose your path
11) When you see the word "ON IN" the trail is complete, the trail has completed and now the real drinking begins.