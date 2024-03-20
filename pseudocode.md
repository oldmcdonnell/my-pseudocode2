
# Object - Check

![Check](/IMG/check.jpg)

# Object - TrailMark

![Trail Mark](/IMG/trailmark.jpg)

# Object - Harrow (hare's arrow)

![Harrow](/IMG/harrow.jpg)

# Object - Beer Near

![Beer Near](/IMG/beernear.jpg)

# Object - Song Check

![Song Check](/IMG/songcheck2.jpg)

# Object - Turkey Eagle split

![Turkey Eagle split](/IMG/turkeyeagle.jpg)

**function searchForMark**  
```javascript
if (trailMark > 3) {
    continue searching
} else {
    blowWhistle
}
```

While searchForMark if markFound relay information to the pack 
- Shout "On 1" for one mark
- Shout "On 2" for two marks
- BlowWhistle for three marks
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

    (beer location * possibility of being discovered by non-hasher = hidding spot++)

    search for beer

**function turkeyEagle**

    - Turkey trails are happy shorter and fun
    - Eagle trails are longer, more dangerous, often wetter
    - Choose at your own peril

# Hash start

1) Init searchForMark, after 3 marks in a row you are on trail, blowWhistle, continue in that direction.
2) If you are lost go back to the last mark and also listen for a whistle.
3) If you see another Hasher searchForMark shout "R U?" They will tell you how many marks they have found since the last check. 
4) If you hear a whistle, run in that direction.
5) If a check is found, init searchForMark again, when trail is found mark check with the correct direction with chalk for the walkers.
6) If a song check is found init songCheck - sing a song.
7) If harrow is found congrats you are on the correct trail, follow the harrow. 
8) If you see Beer Near, init beerNear, search for beer, function songCheck may also apply spontaneosly during beerNear.
9) If you see a Turkey Eagle split, init turkeyEagle, choose your path
10) When you see the word "ON IN" the trail is complete, the trail has completed and now the real drinking begins.