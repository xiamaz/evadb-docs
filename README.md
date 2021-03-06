# EVAdb Documentation

Welcome to the documentation project for EVAdb.

The current version of the documentation is hosted at:

https://brand-fabian.github.io/evadb-docs/

## Contribution

Contributions to the documentation pages are very welcome. For local
development you need a working python installation.

After cloning the repository, use the following commands to run a local
development instance of this documentation and to see your changes reflected
live in your browser.

    pip3 install pipenv
    git clone https://github.com/brand-fabian/evadb-docs.git
    cd evadb-docs/
    pipenv install
    pipenv shell
    cd evadb/
    mkdocs serve 
    # use `mkdocs serve -a 0.0.0.0:8000` if you want to listen on interfaces
    # other than loopback/localhost

Please keep in mind that to add new pages to the documentation, you have to
enter their name and source file in `evadb/mkdocs.yml`.

## Libraries

This documentation is built with `mkdocs` and its `mkdocs-material` theme. For
valid markdown syntax and examples, please see their documentations:

* https://www.mkdocs.org/user-guide/writing-your-docs/
* https://squidfunk.github.io/mkdocs-material/reference/abbreviations/