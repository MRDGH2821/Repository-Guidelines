# Python Project Guideline(s)

It is recommended to use Python v3.8 or above.

## Code Style

Use [PEP-0008 Python Style Guide](https://peps.python.org/pep-0008/)

## Package Manager

Use [PDM](https://pdm.fming.dev/).

## Tools & Configurations

Some configuration rules might not suit to some projects, so it is recommended to convert those rules to warning setting or use the inline disable syntax/comment, wherever applicable.

The rule can also be disabled if it is being inline-disabled in many files.

It is recommended to include the config inside `pyproject.toml` file. Preferably at the bottom of the contents of the file.

### [Pylama](https://klen.github.io/pylama/)

Use the default config. (i.e. no need for dedicated config)

```sh
pip install pylama[all]
```

### [Prettier](https://prettier.io/)

Use My [Prettier config](https://github.com/MRDGH2821/prettier-config-mrdgh2821/blob/main/index.json)

Create a file named `.prettierrc.json` and copy-paste the contents of my config.
It is better this way since the repo doesn't get polluted by npm stuff.

### [Autopep8](https://github.com/hhatto/autopep8)

Use default configuration.

```sh
pip install autopep8
```
