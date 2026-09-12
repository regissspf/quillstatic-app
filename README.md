# quillstatic-app

Static blog generator: markdown in, tidy HTML out

Started as a weekend hack, grew on me.

## What it does

- Index page with post list by date
- Markdown posts with fenced code and tables
- RSS feed generation
- Single template, plain str.format, no Jinja

## Installation

```bash
pip install -r requirements.txt
```

## Usage

```bash
mkdir posts && echo '# hello' > posts/first.md
python build.py
# site lands in dist/
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   ├── development.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── LICENSE
├── SECURITY.md
├── build.py
└── requirements.txt
```

## Development

```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
```

## License

MIT licensed, see LICENSE.
