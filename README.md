## GWU Poster Template

This is a poster template for the [GWU R&D Showcase](https://www.seas.gwu.edu/RDshowcase).
Of course, GWU doesn't provide a proper template but this one is a start. 

## Usage

* `beamerthemeGWU.sty` - this where you can modify the top heading or the running title in the footer
* `poster.tex` - this contains the beamer document which will create the template.
    1. It is a single beamer frame, that is broken up into 3 columns
    2. You can modify the width of each column by adjusting the distances
        ~~~
        \setlength{\onecolwidth}{28cm} % Width of one column
        \setlength{\twocolwidth}{56cm} % Width of two columns
        \newlength{\columnheight}
        \setlength{\columnheight}{76.5cm}
        ~~~
* `poster_packages.sty` - this contains all the packages that are being called. 
Rather than placing it in the preamble it is in a style file. 
This allows one to easily reuse this for other purposes. 

## Tips

* [Linux WikiBook](https://en.wikibooks.org/wiki/Linux_Guide)
* [Beamer Guide](http://tug.ctan.org/macros/latex/contrib/beamer/doc/beameruserguide.pdf)

* It would make sense to [fork](https://help.github.com/articles/fork-a-repo/) this repository and modify it for your own poster. 
This way it is backed up on Github and others can learn or find your good work. 
