<p align="center">
  <a href="https://github.com/dangeroussnake/DangerousSnake">
    <img alt="DangerousSnake" src="https://dangeroussnake.de/res/icon/DangerousSnake144x144.png" width="144">
  </a>
</p>

<p align="center">
  Snake in <b>FORTRAN</b>
</p>

## Description
A simple snake game written in FORTRAN using gfortran and [ncurses for FORTRAN][1].

### Gameplay
<table cellspacing="0" cellpadding="0">
    <tr>
        <td style="text-align: center;">
            <img src="https://dangeroussnake.de/res/gameplay/MainMenu.png" alt="main menu" />
        </td>
        <td style="text-align: center;">
            <img src="https://dangeroussnake.de/res/gameplay/Snake.png" alt="snake" />
        </td>
    </tr>
    <tr>
        <td style="text-align: center;">
            <img src="https://dangeroussnake.de/res/gameplay/SnakeWithAI.png" alt="snake with AI" />
        </td>
        <td style="text-align: center;">
            <img src="https://dangeroussnake.de/res/gameplay/Scores.png" alt="scores" />
        </td>
    </tr>
</table>

## Dependencies
[ncurses port for Fortran 2003][1] (slightly modified)

## Installation

### Installation on Ubuntu
```
sudo apt install gfortran libncurses-dev cmake
git clone https://github.com/dangeroussnake/DangerousSnake.git
mkdir DangerousSnake/build 
(cd DangerousSnake/build && cmake .. && make)
DangerousSnake/bin/snake
```

### Installation on UNIX
- install CMake, gfortran, ncurses
- clone the repository:
```
git clone https://github.com/dangeroussnake/DangerousSnake.git
```
- Run CMake and make:
```
mkdir DangerousSnake/build 
(cd DangerousSnake/build && cmake .. && make)
DangerousSnake/bin/snake
```

## Development
The project is built using [CMake](https://cmake.org/) and [Visual Studio Code](https://code.visualstudio.com/).

Download the following VSCode plugins:
- `ms-vscode.cpptools`
- `twxs.cmake`
- `ekibun.fortranbreaker`
- `krvajalm.linter-gfortran`
- `webfreak.debug`

## About
DangerousSnake and its [website](https://dangeroussnake.de) are developed and maintained by the [DangerousSnake Organization](https://github.com/dangeroussnake).


[1]: http://www.urbanjost.altervista.org/LIBRARY/libscreen/ncurses/pdsrc/ncurses_from_Fortran.html