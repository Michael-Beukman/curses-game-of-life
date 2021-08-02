# Game of Life using NCurses

This is a simple program that starts off with a random state and updates it using the rules set out in [Conway's Game of Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life).

To use it, simply install [ncurses](https://invisible-island.net/ncurses/ncurses.html) and run `make`, followed by `./main`.

Usage is as follows:
```
Usage ./main [CHAR] [SPEED]
    Examples: ./main        -> uses '#' and 60 FPS
    Examples: ./main .      -> uses '.' and 60 FPS
    Examples: ./main . 2    -> uses '.' and 2 FPS
    Examples: ./main ■ 120  -> uses '■' and 120 FPS
```