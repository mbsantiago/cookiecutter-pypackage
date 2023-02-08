{% for _ in cookiecutter.project_name %}={% endfor %}
{{ cookiecutter.project_name }}
{% for _ in cookiecutter.project_name %}={% endfor %}

.. image:: https://img.shields.io/pypi/v/{{cookiecutter.project_name}}.svg
    :target: https://pypi.python.org/pypi/{{cookiecutter.project_name}}/
    :alt: PyPI

.. image:: https://github.com/{{cookiecutter.github_username}}/{{cookiecutter.project_name}}/workflows/Test/badge.svg?branch=main
    :target: https://github.com/{{cookiecutter.github_username}}/{{cookiecutter.project_name}}/actions?query=workflow%3ATest
    :alt: Test Status

.. image:: https://github.com/{{cookiecutter.github_username}}/{{cookiecutter.project_name}}/workflows/Lint/badge.svg?branch=main
    :target: https://github.com/{{cookiecutter.github_username}}/{{cookiecutter.project_name}}/actions?query=workflow%3ALint
    :alt: Lint Status

.. image:: https://codecov.io/gh/{{cookiecutter.github_username}}/{{cookiecutter.project_name}}/branch/main/graph/badge.svg
    :target: https://codecov.io/gh/{{cookiecutter.github_username}}/{{cookiecutter.project_name}}
    :alt: Code Coverage

.. image:: https://img.shields.io/github/license/mashape/apistatus.svg
    :target: https://pypi.python.org/pypi/{{cookiecutter.project_name}}/
    :alt: License

.. image:: https://pepy.tech/badge/{{cookiecutter.project_name}}
    :target: https://pepy.tech/project/{{cookiecutter.project_name}}
    :alt: Downloads

.. image:: https://img.shields.io/badge/code%20style-black-000000.svg
    :target: https://github.com/psf/black
    :alt: Code Style

.. image:: https://img.shields.io/badge/%20imports-isort-%231674b1?style=flat&labelColor=ef8336
    :target: https://timothycrosley.github.io/isort/
    :alt: Imports
_________________

Read Latest Documentation_

.. _Documentation: https://{{cookiecutter.github_username}}.github.io/{{cookiecutter.project_name}}/
_________________

**{{cookiecutter.project_name}}** {{cookiecutter.project_short_description}}
