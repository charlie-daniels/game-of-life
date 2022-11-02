# Game of Life

An interactive game of [Conway's Game of Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life), a zero-player game (determined by beginning state).

## Description

This game is composed of an indeterminite sized 2D orthagonal grid tiles, each one being either live or dead. After each cycle, the state of each _cell_ is altered depending on the state of its neighbours, according to the following set of rules:

1. Any live cell with fewer than two live neighbours dies, as if by **underpopulation**.

2. Any live cell with two or three live neighbours **lives** on to the next generation.

3. Any live cell with more than three live neighbours dies, as if by **overpopulation**.

4. Any dead cell with exactly three live neighbours becomes a live cell, as if by **reproduction**.

## Getting started

### Live preview

Find this site running live on ~~[GitHub Pages]()~~. (Not yet live)

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT) - see the LICENSE.md for more details.
