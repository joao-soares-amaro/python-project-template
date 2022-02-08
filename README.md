<h2 align="center">Python Project Template</h2>

<p align="center">
  <a href="https://github.com/joaogcs/python-project-template/actions"><img alt="Actions Status" src="https://github.com/joaogcs/python-project-template/workflows/CI/badge.svg"></a>
  <a href="https://github.com/relekang/python-semantic-release"><img alt="Semantic Release" src="https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg"></a>
  <a href="https://github.com/joaogcs/python-project-template/blob/main/LICENSE"><img alt="GitHub" src="https://img.shields.io/github/license/joaogcs/python-project-template"/></a>
  <a href="https://open.vscode.dev/joaogcs/python-project-template"><img alt="Open in Visual Studio Code" src="https://open.vscode.dev/badges/open-in-vscode.svg"/></a>
</p>

Template for Python projects with Poetry, automation of semantic release with CI using GitHub Actions.

**Summary**

- [Installation and usage](#installation-and-usage)
  - [Installation](#installation)
  - [Run](#run)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [Change log](#change-log)
- [License](#license)
- [Credits](#credits)

---

## Installation and usage

### Installation

```
pip3 install poetry
```

### Run

```
poetry run python src/main.py
```

### Configuration

You can set up a `pyproject.toml` file to set rules. This is useful to avoid reusing the same CLI flags over and over
again and helps to define the structure of your project.

Example:

```toml
[tool.python-project-template]
variable = "samples"
list-of-variables = ["sample 1", "sample 2", "sample 3"]
boolean-variable = true
```

CLI flags always overwrite the config file.

## Contributing

Thank you for considering making Tryceratops better for everyone!

Refer to [Contributing docs](docs/CONTRIBUTING.md).

## Change log

See [CHANGELOG](CHANGELOG.md).

## License

MIT

## Credits

Thanks to [guilatrova,](https://github.com/guilatrova) and he's project
called [tryceratops](https://github.com/guilatrova/tryceratops) for insights.