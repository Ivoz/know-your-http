# KNOW YOUR HTTP!
## Some posters for your workplace

## Downloads

* [KNOW YOUR HTTP HEADERS!](https://github.com/jesusabdullah/know-your-http/blob/master/headers.pdf?raw=true)
* [KNOW YOUR HTTP METHODS!](https://github.com/jesusabdullah/know-your-http/blob/master/methods.pdf?raw=true)
* [KNOW YOUR HTTP STATUS CODES!](https://github.com/jesusabdullah/know-your-http/blob/master/status-codes.pdf?raw=true)

## Build

To generate the posters, simply run:

    $ make

In order for the build process to be successful, you will need the following:

* LaTeX
* The `beamerposter` and `cclicences` LaTeX packages and their dependencies (if you installed texlive you may already have these installed)
* Make

You can install [TeXLive](https://www.tug.org/texlive/) in Ubuntu by running `sudo apt-get install texlive`. Mac users my try [MacTeX](http://www.tug.org/mactex/), and the preferred distribution for Windows is [MikTeX](http://www.miktex.org/). If you don't have make, you should be able to compile it manually with the `pdflatex` command or similar means.

To generate very large .png versions, run:

    $ make pngs

For this command, you will need `imagemagick` installed. **Only do this if you have no choice as the file sizes are very very large.**

## Licensing:

These posters are licensed [Creative Commons BY-NC-SA](http://creativecommons.org/licenses/by-nc-sa/3.0/) . The big.vc logo itself is copyright The Big Internet Company, all rights reserved, so please do not use it in derivative works.
