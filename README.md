# Unofficial Poster Template for [AILab @ UniTS](https://ai-lab.units.it/) [![Build Status](https://github.com/emaballarin/gemini-ailab-units/workflows/CI/badge.svg)](https://github.com/emaballarin/gemini-ailab-units/actions?query=workflow%3ACI)

A fork of (a [fork](https://github.com/andiac/gemini-cam) of) [Gemini](https://github.com/anishathalye/gemini): a modern LaTeX [beamerposter] theme.

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

1. Make a copy of `beamercolorthemegemini.sty`, update the `\usecolortheme`
   line in `poster.tex`, and theme the poster to your liking (optional, but
   highly recommended)

1. Run `make` to build your poster

## FAQ

See the [FAQ] in the Wiki for answers to frequently asked questions such as how
to add an institution logo to the poster.

## Design goals

* **Minimal**: clean and easy to read, so that the emphasis is on the content
* **Batteries included**: works and looks good out of the box
* **Easy theming**: easy to create and use a new color theme


[beamerposter]: https://github.com/deselaers/latex-beamerposter
[LuaTeX]: http://www.luatex.org/
[CTAN]: https://ctan.org/
[Raleway]: https://www.fontsquirrel.com/fonts/raleway
[Lato]: https://www.fontsquirrel.com/fonts/lato
[FAQ]: https://github.com/anishathalye/gemini/wiki/FAQ
