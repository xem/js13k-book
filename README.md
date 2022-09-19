This book is a compilation of 30 games & emulators golfed with the Codegolf Team and friends, since 2012, aside from js13k.

Compiled in hommage to the authors: Subzey, p01, aemkei, veubeke, xen_the, justecorruptio, damienallonsius, nderscore, ilesinge, sqaxomonophonen, benjamin_js, fusselwurm, parrotgeek1, keithclark, xaotic, ETHproductions, magna, killedbyapixel, jellyedwards and me (xem)

Each game has been regolfed / fixed / enhanced before being included here along with their source code.

Rules:

- MiniSweeper // https://github.com/xem/MiniSweeper
  A little Minesweeper clone
  Numbered cells indicate how many bombs are around it
  Click to clear a cell
  Right-click to flag a cell
  You win if all the bomb cells are flagged
  
- Floppy Dragon (js1k entry) // https://github.com/xem/flappydragon
  Flappy Bird clone
  Click to make the dragon flap
  Pass as many obstacles as possible
  The hitbox is only around its head
  
- PopTiles // https://github.com/xem/minipoptiles
  Click cells in ascending order
  Not super fun but it's based on a real mobile game
  
- 2P Games (js1k entry) // https://github.com/codegolf/2Pgames
  A compilation of 4 games that are played turn-by-turn with the mouse
  * Tic Tac Toe (align 3 identical symbols to win)
  * Tic Tac Toe 3D (align 3 identical symbols to win, including across the 3 boards)
  * Connect 4 (align 4 identical symbols. The coins fall at the bottom)
  * Reversi (flip opponent's coins trapped between two of your coins. The player with the most coins win)
  
- FlappyBraille // https://github.com/codegolf/miniFlappyBraille
  Micro Flappy bird clone (originally played in the address bar, but shown bigger here)
  Press up/down to move the bird vertically
  
- Simon // https://github.com/xem/minisimon
  Remember the sequence of colors and sounds and replay it with Arrow keys
  
- MMXLVIII // https://rawgit.com/veu/603535c10c8516de15cb/raw/4398ed74f2d24fff4648bbb2363526627b4cbd7c/MMXLVIII.html
  2048 clone, play with Arrow keys
  Identical cells are added together, try to reach a total of 2048.
  
- Ping // https://github.com/codegolf/ping
  A single-player Pong clone in ASCII art
  Play with Arrow keys
  
- Pacman // https://github.com/codegolf/pac-man
  A Pac-Man mini clone in ASCII art
  Play with Arrow keys
  
- Tetris // https://github.com/veu/mini-tetris
  A little Tetris clone
  Play with Arrow keys
  
- iniColor // https://codepen.io/xem/pen/QEgGEW
  Click on the wrong color in each grid
  
- Snake // https://github.com/xem/miniSnake
  A mini Snake clone
  Play with Arrow keys
  
- Snake Lite // https://github.com/p01/snake
  A micro Snake clone in ASCII art
  Play with Arrow keys
  
- Binary Tetris // https://gist.github.com/aemkei/1672254
  A micro Tetris clone in ASCII art
  Play with Arrow keys
  
- flap // https://jsbin.com/flap/1/edit?html,output
  A micro Flappy Bird clone in ASCII art
  Press Up to flap
  
- Run // https://github.com/codegolf/Runalakon
  An obstacle course
  Play with Up and Down
  
- Can I Haz 1Karrot? (js1k entry) // https://github.com/xem/1karrot
  A magician's rabbit is lost in a jungle and needs to find its carrot
  Play with Arrow Keys
  
- SN1KE (js1k entry) // https://github.com/xem/miniLOSSST
  A demake of the LOSSST js13k entry, including 50 puzzles
  Move the snake with Arrow Keys, skip level with Shift
  The goal is to match the pattern on the floor
  Puzzles 25-50 include a wrap area for more challenge
  
- MiniTicTacToe // https://ethproductions.github.io/golf/tic-tac-toe/
  A new micro Tic Tac Toe clone for 2 players
  Click a cell to set your symbol
  Align 3 symbols to win
  
- SMB1-1k (js1k entry) // https://github.com/xem/js1k19/tree/gh-pages/SMB1-1k
  A demake of the world 1-1 of Super Mario Bros on NES
  Play with Arrow keys

- SHIFT 2K20 (2KPlus Jam entry) // https://github.com/xem/2kplus20/
  A demake of the original Shift flash game
  Play with Arrow keys. Return the world with Shift key

- MiniWordle // https://github.com/xem/miniWordle/
  A Wordle demake.
  You need to find a random word picked in a list of 52 words
  Write a 5-letter word in the field and press Enter to test it
  Green = good letter, Yellow = misplaced letter, Red = bad letter
  You have 6 attempts. If you lose, the solution appears in the field
  
- Dino (Dwitter entry) // https://www.dwitter.net/d/20814
  A micro demake of the Chrome offline dino game
  Click to make the dino jump over cactii

- Lights out (Dwitter entry) // https://www.dwitter.net/d/22102
  Click a lightbulb to toggle it and its 4 neighbours
  Can you turn all the lights off in less than 13 clicks?
  
- MiniGameOfLife // https://github.com/xem/miniGameOfLife
  Our smallest Game of Life simulation (auto played)
  
- Chip8 emulator // https://github.com/xem/chip8
  A full emulator for the Chip8 retro/fantasy console
  Collection of public domain roms: http://codegolf.github.io/js13kGamePak/ROM.zip
  Click the visual keyboard to play
  
- NES emulator (WIP) // https://github.com/xem/jsnes-lite
  A work in progress NES emulator without sound
  Bring your own roms (commercial or homebrew)
  Only emulates the "Mapper 0" roms (<= 40kb) like Super Mario Bros, Donkey Kong, Galaga, Ice Climbers, etc.
  Play with X + C + Arrow Keys + Enter + Escape
