# PonyDrinkingCardGame
Somehow this crazy idea actually became playable game.

![Graphics](https://raw.githubusercontent.com/HalfTough/PonyDrinkingCardGame/master/img.png)

Here you can find sources of free card game for adults inspired by 4chan Drinking Game and themed around *My Little Pony: Friendship is Magic*.
Sources are useful for creating your own cards or translating/editing existing ones.

If you want to play the game, you can download ready to print version at https://mega.nz/#F!ALZCATaJ!H2q2ZxJopOUqxocWb7sh4g.

## Dependences
Script was created with Linux in mind. It might work on OS X, but I haven't tested it.  
[Python](https://www.python.org/) >=3.5  
[Imagemagick](https://www.imagemagick.org/script/index.php) 6.9.9-19 (It most likely will work under other versions, but at some point I had to downdrade becouse of a bug)

### Fonts
[Equestria](https://www.dafont.com/equestria.font)  
[Noto Sans Display](https://www.google.com/get/noto/#sans-lgc-display)  
Z003

## Usage
Start by downloading or cloning project.

To generate deck, simply run  
```python generate.py```

To generate cards using text from subdirectory (e.g. cards/pl) run  
```python generate.py --language {dir}```

## How to play
### Short version:  
Draw a card:  
Pony Card – stays with you. Gets replaced when you draw new Pony Card.  
Magic Card – put it in your hand, without showing it to other players. Use later.  
Action Card – do what it says.  
Friendship Card – Same as Action Card but applies to all players.  
After your turn is over, next player draws a card and so on...

Before the game starts, you should decide how you define *a shot* and *a drink*.
### Long version:
https://mega.nz/#!JWYWWBjZ!ak_VBBpCFguPZarbPuLVZc7TkQfPv_SpComUPWM5fp8

## TODOS
* Windows
* Engrish, motherfucker, do you speak it?
