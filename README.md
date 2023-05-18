# TestbeamDocumentation
Source code for documentation of fast timing testbeams hosted [here](https://cms-mtd.github.io/TestbeamDocumentation/)

### Requirements
MkDocs requires a recent version of Python and the Python package manager, pip, to be installed on your system.
You can check if you already have these installed from the command line:

```shell
$ python --version
Python 3.8.2
$ pip --version
pip 20.0.2 from /usr/local/lib/python3.8/site-packages/pip (python 3.8)
```
## Plugin installation for mkdocs
pip install mkdocs
pip install mkdocs-material
pip install mkdocs-markdownextradata-plugin==0.2.5
pip install mkdocs-git-revision-date-localized-plugin
pip install mkdocs-awesome-pages-plugin
pip install mkdocs-minify-plugin


### Documentation Building
Delete or comment out following text in mkdocs.yml
```shell
 - search:
      min_search_length: 2
```

```shell
$ mkdocs build --strict
```
Which creates a directory site/ containing static HTML pages. To start a server to browse the pages, run
```shell
$ mkdocs serve --dev-addr localhost:8000
```
and open your webbrowser at http://localhost:8000. By default, all pages are automatically rebuilt and reloaded when a source file is updated.
