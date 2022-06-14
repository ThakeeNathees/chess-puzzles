## Chess Puzzles

A chess puzzles game written in [pocketlang](https://github.com/ThakeeNathees/pocketlang)
using [raylib](https://github.com/raysan5/raylib) for graphics. All the puzziles
are downloaded from [lichess database](https://database.lichess.org/). Currently I've
added only about 1000 puzzles however you could add more puzzles to `res/lichess_db.csv`
downloading from the lichess puzzles database.

<img src="https://user-images.githubusercontent.com/55296050/173678474-62321157-36fb-4a35-9d09-dca936693ed7.gif" width="50%">

To run the application you need [pocketlang](https://github.com/ThakeeNathees/pocketlang)
and [raylib-pocket](https://github.com/ThakeeNathees/raylib-pocket) library
place the compiled raylib-pocket binary `raylib.dll` or `raylib.so`
the pocketlang searchpath (`./raylib.dll`, `./raylib/_init.dll`,
`<pocket-exe-dir>/libs/raylib.dll`, `<pocket-exe-dir>/libs/raylib/_init.dll`, etc)
and run the main script using the bellow command.

```
pocket main.pk
```

This has developed and tested only on windows however this supposed to work on
all major plaforms. 
