# Material on a Talk about Typography

This is the material for a talk about typography held at the 3. GPN (private) converence of the F3L-Community, 11.06.2016, University of Regensburg.

It is meant as a short reference and overview on what typographical topics could and should be considered when creating documents of any type. A couple of tipps for common applications are included.

Please note, that some of the example documents will not be published due to privacy reasons.


## Prerequesites
The material was compiled to pdf using the **TeXLive2016**-distribution of LaTeX. Furthermore, the following **fonts** should be installed as .ttf or .otf and accessible by lualatex:

- [Computer Modern Roman](https://www.fontsquirrel.com/fonts/computer-modern) (standard in LaTeX)
- [Latin Modern Roman](https://www.fontsquirrel.com/fonts/Latin-Modern-Roman)
- [Droid Serif](https://www.fontsquirrel.com/fonts/droid-serif)
- [Roboto Slab Regular](https://www.fontsquirrel.com/fonts/roboto-slab)
- [Fira Sans Regular](https://github.com/mozilla/Fira)
- [Unifraktur Maguntia](http://unifraktur.sourceforge.net/maguntia.html#download_and_installation)


## Compilation

The main files are `typography_article.tex` (for the handout-version) and `typography_beamer.tex` (for the presentation).
These are compiled in a terminal (compile **at least twice** to ensure that the internal pdf-links work correctly) with the command:

> lualatex typography_beamer.tex typography_article.tex


## Modification

### Aspect Ration
To adjust the aspect ratio of the beamer presentation, uncomment and modify the option `aspectratio=169` in the file `typography_beamer.tex`. Standard will be *4:3* (`aspectratio=43`), another possible option is *16:9* (`aspectratio=169`). For more options consult the [documentation of the beamer-package](http://texdoc.net/texmf-dist/doc/latex/beamer/doc/beameruserguide.pdf).

### Styles of Presentation/Handout
The corresponding styles are configured in the files `typography_article.tex` and `typography_beamer.tex`.

### Content
The actual content is contained in the file `typography.tex`.
