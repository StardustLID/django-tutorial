# django-tutorial
My attempt at Django's tutorial, which makes a poll app.

## Project structure
```bash
.
├── mysite                          # actual Python package for the project. Its name is the Python package name
│                                   # you’ll need to use to import anything inside it (e.g. mysite.urls).
│   ├── __init__.py
│   ├── asgi.py                     # entry-point for ASGI-compatible web servers to serve the project
│   ├── settings.py                 # settings/config for this Django project
│   ├── urls.py                     # URL declarations for this Django project; a “table of contents” of your Django-powered site
│   └── wsgi.py                     # entry-point for WSGI-compatible web servers to serve the project
├── cookbook                        # useful code snippets written in notebooks
│   ├── data                        # data (gitignored, content omitted)
│   ├── subgraph_examples.ipynb     # implementation of Uniswap V3 subgraph tutorial
│   └── vertex_degrees.ipynb        # analysis of connectedness of Uniswap V3 tokens
├── .gitignore                      # ignore files that cannot be committed to Git
├── LICENSE                         # MIT license file
├── manage.py                       # A command-line utility that lets you interact with this Django project
└── README.md                       # this file
```
