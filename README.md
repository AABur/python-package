# python-package

[![Github Actions Status](https://github.com/AABur/python-package/workflows/Python%20CI/badge.svg)](https://github.com/AABur/python-package/actions)
[![Maintainability](https://api.codeclimate.com/v1/badges/df66c0cbbeca7d822f23/maintainability)](https://codeclimate.com/github/hexlet-boilerplates/python-package/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/df66c0cbbeca7d822f23/test_coverage)](https://codeclimate.com/github/hexlet-boilerplates/python-package/test_coverage)

A modern Python package template following current best practices.

## Features

- **Modern Package Structure**: Uses the proven flat layout with clear separation of concerns
- **Poetry Dependency Management**: Modern dependency management and packaging
- **PEP 621 Compliance**: Uses the standard `[project]` table in `pyproject.toml`
- **Multi-Python Support**: Tested on Python 3.8, 3.9, 3.10, 3.11, and 3.12
- **Type Hints**: Fully typed codebase for better development experience
- **Testing**: Comprehensive test suite with pytest and coverage reporting
- **Code Quality**: Automated linting with flake8 and formatting with autopep8
- **CI/CD**: GitHub Actions workflow for automated testing and quality checks
- **MIT Licensed**: Open source friendly licensing

## Installation

### From source
```bash
git clone https://github.com/AABur/python-package.git
cd python-package
poetry install
```

### For development
```bash
git clone https://github.com/AABur/python-package.git
cd python-package
poetry install --with dev
```

## Usage

### As a library
```python
from hexlet_python_package.user import User

user = User("Alice", 25)
print(user.get_introduction())
# Output: Hello, i'm Alice, 25
```

### As a CLI tool
```bash
poetry run hexlet-python-package
# Output: Hello, i'm Bob, 42
```

## Development

### Running tests
```bash
make test
```

### Running linter
```bash
make lint
```

### Running all checks
```bash
make check
```

### Coverage report
```bash
make test-coverage
```

### Building the package
```bash
make build
```

## Tools Used

This project was built using these modern tools:

| Tool                                                                        | Description                                             |
|-----------------------------------------------------------------------------|---------------------------------------------------------|
| [poetry](https://python-poetry.org/)                                       | "Python dependency management and packaging made easy"  |
| [pytest](https://pytest.org)                                               | "A mature full-featured Python testing tool"            |
| [flake8](https://flake8.pycqa.org/)                                        | "Python code linting and style checking"                |

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### Links

This project was built using these tools:

| Tool                                                                        | Description                                             |
|-----------------------------------------------------------------------------|---------------------------------------------------------|
| [poetry](https://poetry.eustace.io/)                                        | "Python dependency management and packaging made easy"  |
| [Py.Test](https://pytest.org)                                               | "A mature full-featured Python testing tool"            |
| [wemake-python-styleguide](https://wemake-python-stylegui.de)               | "the strictest and most opinionated python linter ever" |

[![Hexlet Ltd. logo](https://raw.githubusercontent.com/Hexlet/assets/master/images/hexlet_logo128.png)](https://ru.hexlet.io/pages/about?utm_source=github&utm_medium=link&utm_campaign=python-package)

This repository is created and maintained by the team and the community of Hexlet, an educational project. [Read more about Hexlet (in Russian)](https://ru.hexlet.io/pages/about?utm_source=github&utm_medium=link&utm_campaign=python-package).
