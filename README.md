# mainzed tools Docs

This repository provides the documentation for the mainzed tools build using Read The Docs.

Get the latest `build` [here](https://htmlpreview.github.io/?https://raw.githubusercontent.com/mainzed/tools-docs/master/de/build/html/index.html).

## Setup

* [getting started](https://docs.readthedocs.io/en/latest/getting_started.html)
* install python
  * https://www.python.org/downloads/
  * http://www.sphinx-doc.org/en/stable/install.html
* write python in PATH variable (Umgebungsvariaben)
* test in cmd `> python`
* install pip command `> python get-pip.py` [get file](https://bootstrap.pypa.io/get-pip.py)
  * pip has been contained in the Python official installation after version of Python-3.4.0 or Python-2.7.9.
* install sphinx with pip `> pip install sphinx`
* test in cmd `> sphinx-build -h`
* install sphinx autobuild `> pip install sphinx sphinx-autobuild`
* install markdown support `> pip install recommonmark`
* install theme `> pip install sphinx_rtd_theme`

## Rund and Build

* go to git folder with rtd content in cmd `> cd de`
  * clear: `make clean`
  * create: `make html`

## Credits

```
Florian Thiery M.Sc.
- Institut für Raumbezogene Informations- und Messtechnik (i3mainz)
- Römisch-Germanisches Zentralmuseum, Leibniz-Forschungsinstitut für Archäologie (RGZM)
- Mainzer Zentrum für Digitalität in den Geistes- und Kulturwissenschaften (mainzed)
```
