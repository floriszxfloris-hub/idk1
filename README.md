# idk1

A tiny Snake game in a single, dependency-free `index.html`.

## Play

Open `index.html` in a browser, or serve the folder and visit http://localhost:8000:

```sh
python3 -m http.server 8000
```

## Controls

| Action | Keyboard | Touch |
| --- | --- | --- |
| Move | Arrow keys or WASD | Swipe on the board or use the on-screen arrows |
| Pause / resume | Space, P or Esc | Pause button, then **Resume** |
| Start / play again | Space or Enter (an arrow key also starts the first game) | **Play** / **Play again** |

Each apple is worth a point and makes the snake a little faster. Hitting a wall or your own tail ends the game. Your best score is saved in the browser.
