# CUHKthesis
A simple LaTeX template for CUHK thesis based on [CUHK format guide](https://www.gradsch.cuhk.edu.hk/pgstudent/gsinfo/research/Chapter%206.html#Chapter6).

## Install
1.  Download or clone this repository.
2.  Compile `thesis.tex` with [XeLaTeX](https://www.overleaf.com/learn/latex/XeLaTeX) (already included in major TeX distributions). Then you will get the [demo](thesis.pdf).

## Usage

Edit the corresponding `.tex` files with your favorite editor and compile `thesis.tex` with XeLaTeX. 

### Directory structure 
|   Direcotry   |                   Description                   |
| :-----------: | :---------------------------------------------: |
|  `preamble/`  |            for settings and commands            |
|   `pages/`    | abstract, Chinese abstract, and acknowledgement |
|  `chapters/`  |            major separated chapters             |
| `appendices/` |                   appendices                    |
|  `figures/`   |    the suggested folder for inserted figures    |
| `reference/`  |      `.bib` database and `.bst` style file      |

### Settings and commands
- You can change the formats and styles of the thesis by adjusting the settings in `preamble/settings.tex`.
- The commands for fast-typing are stored in `preamble/usrcmds.tex`. Users can define their own commands in this file.
- Usually we don't have to modify `preamble/cmds.tex` since it only contains commands for outputting standard pages.

---
> Any issues or pull requests are welcome.
