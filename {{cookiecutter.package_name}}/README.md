# {{ cookiecutter.package_name }}

{% if cookiecutter.readme_pypi_badge == 'y' -%}
[![Latest PyPI version](https://img.shields.io/pypi/v/package_name.svg)](https://pypi.python.org/pypi/{{ cookiecutter.package_name }})

{% endif -%}
{% if cookiecutter.readme_travis_badge == 'y' -%}
[![Latest Travis CI build status]({{ cookiecutter.readme_travis_url }}.png)]({{ cookiecutter.readme_travis_url }})

{% endif -%}
{% if cookiecutter.package_description != '' -%}
{{ cookiecutter.package_description }}

{% endif -%}
## Usage

## Installation

### Requirements

## Compatibility

## Licence

## Authors

{{ cookiecutter.package_name }} was written by [fx-kirin](fx.kirin@gmail.com).
