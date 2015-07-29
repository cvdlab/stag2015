# STAG 2015 paper

## virgafox/texlive docker instructions

Check that docker is up and running, and `virgafox/texlive` has been correctly pulled down (Dockerfile can be used to build the image), than:

to run `pdflatex`, issue:

```
docker run --rm -v `pwd`:/tmp virgafox/texlive pdflatex stag-2015
```

to run `bibtex`, issue:

```
docker run --rm -v `pwd`:/tmp virgafox/texlive bibtex stag-2015
```
