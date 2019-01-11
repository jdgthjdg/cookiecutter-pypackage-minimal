{{ cookiecutter.package_name }}
{{ cookiecutter.package_name|count * "=" }}

{% if cookiecutter.readme_pypi_badge == 'y' -%}
[![Latest PyPI version](https://img.shields.io/pypi/v/package_name.svg)](https://pypi.python.org/pypi/package_name)

{%- endif %}
{% if cookiecutter.readme_travis_badge == 'y' -%}
[![Latest Travis CI build status]({{ cookiecutter.readme_travis_url }}.png)]({{ cookiecutter.readme_travis_url }})

{%- endif %}
{{ cookiecutter.package_description }}

Usage
-----

Installation
------------

### Requirements

Compatibility
-------------

Licence
-------

Authors
-------

package\_name was written by [fx-kirin](fx.kirin@gmail.com).
