# Remember the Milk workflow for Alfred

This is a small workflow that leverages Tim Pope's [rumember](https://github.com/tpope/rumember) to quickly add tasks to [Remember the Milk](https://www.rememberthemilk.com) via [Alfred](https://www.alfredapp.com/)

It is *heavily* based on [Matthew O'Riordan's workflow](http://www.alfredforum.com/topic/3648-remember-the-milk/)/[GitHub](https://github.com/mattheworiordan/alfred-remember-the-milk-plugin), with a few changes:

* uses zsh instead of bash
* different icon (which I prefer in the Solarized-Dark theme I use with Alfred)
* only add the directory to $PATH if `ru` exists in the directory
* adds $HOME/.rbenv/shims as one of the possible locations of `ru`

(that last one is what prompted making a new workflow)

Note: this workflow requires that you have rumember installed and authenticated
