# Authors

## Authors
{% for foo in cookiecutter.authors.split(",") %}
* {{ foo.replace(" ", "") }} - <{{ cookiecutter.emails.split(",")[loop.index - 1].replace(" ", "") }}>
{% endfor %}

## Project Contributors

