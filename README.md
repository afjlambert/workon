# Workon

Project-management for your shell.

Keywords: bash, shell, cli, pm, project management, navigation

This tool is build for people who work on multilpe projects and wish to speed up their development workflow.


## Install


```bash
source path/to/workon
```

## TODO

- cleanup
- `work delete` prompt does not play nice with shell wrapper
- deactivate previous project before 'on'?
- support custom names to prevent duplicate folder names
  - support 'rename' command
- make tests
- Make install file using `curl`
- bash-completion `workon [tab][tab]p[tab]` etc.


## Usage

```bash
workon --help
```

## Push to pypi

```bash
rm -rf dist
python setup.py sdist bdist_wheel
twine upload --repository-url https://upload.pypi.org/legacy/ dist/*
```
