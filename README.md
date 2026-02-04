# sefer-torah-online

[![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white)](https://github.com/pre-commit/pre-commit)

A bilingual (Hebrew-Spanish) online resource for Torah study, featuring prayers, blessings, and parashot from the Jewish tradition.

## Live Site

Visit the live site at: [https://lalgonzales.github.io/sefer-torah-online](https://lalgonzales.github.io/sefer-torah-online)

## Project Structure

- `content/`: Source files for prayers, blessings, and parashot
- `styles/`: Custom CSS styles
- `_quarto.yml`: Quarto configuration
- `index.qmd`: Homepage

## Building the Site

This project uses [Quarto](https://quarto.org/) to generate a static website.

### Prerequisites

- [Quarto](https://quarto.org/docs/get-started/) installed
- Git

### Build

```bash
quarto render
```

### Preview Locally

```bash
quarto preview
```

### Deploy

The site is deployed via GitHub Pages. Push to main branch to trigger deployment.

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make changes
4. Submit a pull request

## License

[Add license if applicable]
