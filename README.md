# quillstatic

My tiny static site generator, ~100 lines of Python

Side project, maintained when I have time.

## Install

```bash
pip install -r requirements.txt
```

## Highlights

- Markdown posts with fenced code and tables
- RSS feed generation
- Single template, plain str.format, no Jinja
- Index page with post list by date

## Examples

```bash
mkdir posts && echo '# hello' > posts/first.md
python build.py
# site lands in dist/
```

## Project structure

```text
├── docs/
│   ├── configuration.md
│   └── development.md
├── examples/
│   └── quickstart.md
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
├── build.py
└── requirements.txt
```

## Development

```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
```

## License

MIT - see [LICENSE](LICENSE).
