The chords are stored in a format like this:

```
chords: {
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

Most chords be in this library. I'm currently missing slash chords. But I'm making a plan on how to generate them, to add them too.
