# Template MkDocs Starter Project

{{ brief docs description }}
## View Docs

To view the documentation represented in this project visit:

{{ path to output pages url }}
## Development

This documentation project was create with [MkDocs](http://www.mkdocs.org/) using the [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) theme.


## Run with MkDocs

Clone this project to run the site locally.

### Requirements

MkDocs & Them:

```shell
pip install mkdocs
pip install mkdocs-material
```

Then run:

```shell
mkdocs serve
```

and view the site at [http://127.0.0.1:8000](https://127.0.0.1:8000).

## Run Docker

Build:

```shell
docker build . -t docs
```

Run:

```shell
docker run -it -p 8000:8000 docs
```

then view the site at [http://0.0.0.0:8000](https://0.0.0.0:8000).

## Automation

Updates to this repo will generate an update to the docs when commits are merged to the default branch (main/master).

## Contribution

To make changes to this project, please follow appropriate protocol to track history.

1. Fork/Clone the Project: `git clone {{repo url}}`
2. Create your Feature Branch: `git checkout -b feature/AmazingFeature`
3. Commit your Changes: `git commit -m 'Add some AmazingFeature'`
4. Push to the Branch: `git push origin feature/AmazingFeature`
5. Open a Pull Request
6. If required, request review of PR and have a second individual Pull the change

### Road Map and Open Issues

See the [open issues](../../issues) for a list of proposed updates.
