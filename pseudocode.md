Object | Image
------------ | -------------
Check | ![Check](/IMG/check.jpg)
Trail Mark | ![Trail Mark](/IMG/trailmark.jpg)
Harrow (hare's arrow) | ![Harrow](/IMG/harrow.jpg)
Beer Near | ![Beer Near](/IMG/beernear.jpg)
Song Check | ![Song Check](/IMG/songcheck2.jpg)
Turkey Eagle split | ![Turkey Eagle split](/IMG/turkeyeagle.jpg)


**function haresAway**  

    -wait 10 minutes while Hares start the trail

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

1) Introductions, everyone introduces themselves, local rules are explained
2) Blessing of the Hares
3) Init haresAway, wait 10 miutes
4) Init searchForMark, after 3 marks in a row you are on trueTrail, blowWhistle,  continue in that direction.
5) If you are lost - go back to the last mark - listen for a whistle.
6) If you see another Hasher searchForMark shout "R U?" They will tell you how many marks they have found since the last check. 
7) If you hear a whistle, run in that direction.
8) If a check is found, init searchForMark again, when trail is found use chalk to mark the check with the correct direction for the walkers.
9) If a song check is found init songCheck - sing a song.
10) If Harrow is found congrats you are on trueTrail, follow the harrow. 
11) If you see Beer Near, init beerNear, search for beer, function songCheck may also apply spontaneosly during beerNear.
12) If you see a Turkey Eagle split, init turkeyEagle, choose your path
13) When you see the word "ON IN" the trail is complete, the trail has completed and now the real fun begins.