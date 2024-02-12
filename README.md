# Uni Bremen Theme based on Gemini 

This is a adapted version of the Gemini modern LaTeX [beamerposter] theme, it uses the official colors from the Uni Bremen CI.

<p align="center">
<a href="https://raw.githubusercontent.com/anishathalye/assets/master/gemini/poster-gemini.pdf">
<img src="https://raw.githubusercontent.com/anishathalye/assets/master/gemini/poster-gemini-small.png">
</a>
</p>

If you're looking for a beamer presentation theme for the uni bremen, take a look at (https://gitlab.informatik.uni-bremen.de/vorlagen/latex-beamer-theme)[Uni Bremen Presentation Theme].

## Dependencies

* A TeX installation that includes [LuaTeX]
    * You also need `latexmk` if you want to use the provided `Makefile`
* LaTeX package dependencies including beamerposter (these usually come with
  your TeX installation, but if not, you can get them from [CTAN])
* [Raleway] and [Lato], which are both available under Open Font License

## Usage

1. Copy the files in this repository (or clone the repository)

1. In `poster.tex`, set up your paper size, column layout, and scale the
   content as necessary

1. Run `make` to build your poster

Copyright (c) 2024 Linus Andrae. Released under the MIT Licence. See
[LICENSE.md][license] for details.
Copyright (c) 2018-2022 Anish Athalye. Released under the MIT License. See
[LICENSE.md][license] for details.

[beamerposter]: https://github.com/deselaers/latex-beamerposter
[Auriga]: https://github.com/anishathalye/auriga
[LuaTeX]: http://www.luatex.org/
[CTAN]: https://ctan.org/
[Raleway]: https://www.fontsquirrel.com/fonts/raleway
[Lato]: https://www.fontsquirrel.com/fonts/lato
[license]: LICENSE.md
[FAQ]: https://github.com/anishathalye/gemini/wiki/FAQ
