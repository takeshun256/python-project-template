# python-project-template

## Requirements
* Poetry(>=1.16)
* Python(>=3.7.x)

## Usage

### Enable Visual Studio Code settings

```bash
cp .vscode/settings.default.json .vscode/settings.json
```

### Add package
```bash
poetry add [package name]
```

### Install dependency

development
```bash
poetry install
```

production
```bash
poetry install --no-dev
```
