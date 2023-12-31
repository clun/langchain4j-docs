# Langchain4j Documentation

 [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

Static site is generated on branch `gh-pages` using a github actions.

## Run the website locally

### 1. Installation

```bash
python3 -m pip install --upgrade pip     # install pip
python3 -m pip install mkdocs            # install mkdocs 
python3 -m pip install mkdocs-material   # install material theme
python3 -m pip install mkdocs-git-revision-date-plugin # install git revision date
python3 -m pip install mkdocs-video # install git revision date
```

Or use this one-liner :) 

```
python3 -m pip install --upgrade pip && python3 -m pip install mkdocs mkdocs-material https://github.com/bmcorser/fontawesome-markdown/archive/master.zip mkdocs-git-revision-date-plugin
```

### 2. Run

```
mkdocs serve
```

You should be able to access it on http://localhost:8000

**Known Issue:**

If you get an `mkdocs not found error`, launch it this way: 

```
python3 -m mkdocs serve
```
