The chords are stored in the following JSON format:

```
{
    "C#":[{
        "positions": ["x","4","6","6","6","4"],
        "fingerings": [["0","1","3","3","3","1"], ["0","1","2","3","4","1"]]
    },{
        "positions": ["9","11","11","10","9","9"],
        "fingerings":[["1","3","4","2","1","1"]]
    }, ...],
    "C#m":[{
        "positions":["x","4","6","6","5","4"],
        "fingerings":[["0","1","3","4","2","1"]]
    },{
        "positions":["9","11","11","9","9","9"],
        "fingerings":[["1","3","4","1","1","1"]]
    }, ...],
    ...
}
```

For a usage example please refer to my [Chord-Draw](https://github.com/t-vk/Chord-Draw.git) project.

If you want a complete list of all chords with all it's shapes, then go ahead and use `chords.complete.json` (~ 13.5MB !!!) or `chords.complete.js` (~ 13.5MB !!!).  
If you want a list of all chords and one shape per chord is enough for you, then you should use `chords.json` (~ 1.2MB !) or `chords.js` (~ 1.2MB !).

This chord library has been created with the help of jguitar.com. Which is a really awesome website that goes far beyond what this project could offer. You should defintiely check it out and consider supporting them!

## License
The source is licensed under the GPL.
