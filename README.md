# Project Name

Write a brief description of the project, explaining what it does in a couple of sentences.

Add a [build status badge](https://docs.travis-ci.com/user/status-images/) from Travis-CI

## Getting Started

Describe the installation or setup process, using `inline code blocks` to indicate terminal commands.

## Usage

Add usage instructions, including configuration details, settings or arguments available.

## License

Add license. Where possible, specify that the code is released under the MIT License. Then edit `MIT-LICENSE.md` included in this repository to include the date and include it in your repository as `LICENSE.md`.

## Contributing

Add information about how to contribute to the project, such as by filing an issue or submitting a pull request.

If relevant, include standards for contributing code. This may include:

* style guidelines
* pre-commit configuration
* documentation
* tests

### Example: Python

#### Contribution standards

##### Style

This project uses the Python PEP8 community style guidelines. To conform to these guidelines, the following linters are part of the pre-commit:

* autopep8 formats the code automatically
* flake8 checks for style problems as well as errors and complexity
* isort sorts imports alphabetically, and automatically separated into sections and by type

After locally installing pre-commit, install the git-hook scripts in the project's directory:

    ```
    pre-commit install
    ```  

##### Documentation

Docstrings should explain what a module, class, or function does by explaining its syntax and the semantics of its components. They focus on specific elements of the code, and less on how the code works. The point of docstrings is to provide information about the code you have written; what it does, any exceptions it raises, what it returns, relevant details about the parameters, and any assumptions which might not be obvious. Docstrings should describe a small segment of code and not the way the code is implemented in a larger environment.

This project adheres to [Google’s docstring style guide](https://google.github.io/styleguide/pyguide.html#381-docstrings). There are two types of docstrings: one-liners and multi-line docstrings. A one-line docstring may be perfectly appropriate for obvious cases where the code is immediately self-explanatory. Use multiline docstrings for all other cases.

##### Tests [Python Scripts]

New code should  have unit tests. Tests are written in unittest style and run using [tox](https://tox.readthedocs.io/).

##### Tests [Django Applications]

New code should  have unit tests. Tests are written in unittest style and use the Django-provided [TestCase](https://docs.djangoproject.com/en/4.0/topics/testing/overview/). Tests are run using `manage.py`.

