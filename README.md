# jupyterlab_spellchecker_fr

<div class="alert alert-warning"
I needed a spell checker for French so I forked https://github.com/ijmbarr/jupyterlab_spellchecker and modified 3 lines (4 if you count the color). 
</div> 

A JupyterLab extension highlighting misspelled words in markdown cells within notebooks.

![](demo.gif)

The JupyterLab extension is based on [the spellchecker Jupyter Notebook extension](https://github.com/ipython-contrib/jupyter_contrib_nbextensions/tree/master/src/jupyter_contrib_nbextensions/nbextensions/spellchecker) and relies on [Typo.js](https://github.com/cfinke/Typo.js) for the actual spell checking.

The extension currently only use the `en_US` dictionary loaded from the [jsdelivr.net cdn](https://www.jsdelivr.com/).

## JupterLab Version
The extension has been tested up to JupyterLab version 2.0.0.

## Installation

=> to be updated if it works

```bash
jupyter labextension install @ijmbarr/jupyterlab_spellchecker
```

## Development

For a development installation (requires npm version 4 or later), do the following in the repository directory:

```bash
npm install
npm run build
jupyter labextension link .
```

To rebuild the package and the JupyterLab app:

```bash
npm run build
jupyter lab build
```
