[![img](https://img.shields.io/github/contributors/MArpogaus/python-project-skeleton.svg?style=flat-square)](https://github.com/MArpogaus/python-project-skeleton/graphs/contributors)
[![img](https://img.shields.io/github/forks/MArpogaus/python-project-skeleton.svg?style=flat-square)](https://github.com/MArpogaus/python-project-skeleton/network/members)
[![img](https://img.shields.io/github/stars/MArpogaus/python-project-skeleton.svg?style=flat-square)](https://github.com/MArpogaus/python-project-skeleton/stargazers)
[![img](https://img.shields.io/github/issues/MArpogaus/python-project-skeleton.svg?style=flat-square)](https://github.com/MArpogaus/python-project-skeleton/issues)
[![img](https://img.shields.io/github/license/MArpogaus/python-project-skeleton.svg?style=flat-square)](https://github.com/MArpogaus/python-project-skeleton/blob/main/LICENSE)
[![img](https://img.shields.io/github/actions/workflow/status/MArpogaus/python-project-skeleton/test.yaml.svg?label=test&style=flat-square)](https://github.com/MArpogaus/python-project-skeleton/actions/workflows/test.yaml)
[![img](https://img.shields.io/badge/pre--commit-enabled-brightgreen.svg?logo=pre-commit&style=flat-square)](https://github.com/MArpogaus/python-project-skeleton/blob/main/.pre-commit-config.yaml)
[![img](https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555)](https://linkedin.com/in/MArpogaus)

[![img](https://img.shields.io/pypi/v/minimal-python-project-skeleton.svg?style=flat-square)](https://pypi.org/project/minimal-python-project-skeleton)


# Minimal Python Project Skeleton

1.  [About The Project](#org6f62e8e)
2.  [Getting Started](#orgee5d15d)
    1.  [Installation](#orgc2cc14f)
3.  [Contributing](#org7a2117b)
4.  [License](#org8214d5f)
5.  [Contact](#orge7c5b87)
6.  [Acknowledgments](#org06a507d)


<a id="org6f62e8e"></a>

## About The Project

This folder structure should act as a simple starting point for your next python project.

    .
    ├── .github
    │   └── workflows
    │       ├── pre-commit.yaml
    │       ├── release.yaml
    │       └── test.yaml
    ├── .gitignore
    ├── .pre-commit-config.yaml
    ├── CONTRIBUTING.md
    ├── LICENSE
    ├── README.md
    ├── README.org
    ├── pyproject.toml
    ├── src
    │   └── minimal_python_project_skeleton
    │       └── __init__.py
    └── test
        └── test_func.py

    6 directories, 12 files

It contains just the minimum to get you started with a ready configured GitHub actions for automated [linting](<https://github.com/MArpogaus/minimal-python-project-skeleton/blob/main/.github/workflows/pre-commit.yaml>), [testing](<https://github.com/MArpogaus/minimal-python-project-skeleton/blob/main/.github/workflows/test.yaml>), and [releasing](<https://github.com/MArpogaus/minimal-python-project-skeleton/blob/main/.github/workflows/release.yaml>) on PiPy.


<a id="orgee5d15d"></a>

## Getting Started

Use this template directly to [create a new GitHub repository](<https://github.com/new?template_name=minimal-python-project-skeleton&template_owner=MArpogaus>) or just clone the repository to your desired destination and start working on your new project.

**Pro-Tipp:** If you later want to update the template, keep a separate branch (i.e. `skeleton`) around and `cherry-pick` the changes you would like to keep for future projects.
This way you can also pull the latest version from upstream and `checkout` the new files you would like to use in your project.


<a id="orgc2cc14f"></a>

### Installation

This package is available on [PyPI](https://pypi.org/project/minimal-python-project-skeleton/). You install it using pip:

    pip install minimal_python_project_skeleton


<a id="org7a2117b"></a>

## Contributing

Any Contributions are greatly appreciated! If you have a question, an issue or would like to contribute, please read our [contributing guidelines](CONTRIBUTING.md).


<a id="org8214d5f"></a>

## License

Distributed under the [MIT License](LICENSE)


<a id="orge7c5b87"></a>

## Contact

[Marcel Arpogaus](https://github.com/MArpogaus/) - [znepry.necbtnhf@tznvy.pbz](mailto:znepry.necbtnhf@tznvy.pbz)

Project Link:
<https://github.com/MArpogaus/python-project-skeleton>


<a id="org06a507d"></a>

## Acknowledgments

-   README inspired by [othneildrew/Best-README-Template](https://github.com/othneildrew/Best-README-Template)
-   Contribution guidelines inspired by [probabilists/zuko](https://github.com/probabilists/zuko/)
-   Release workflow inspired by [packaging.python.org](https://packaging.python.org/en/latest/guides/publishing-package-distribution-releases-using-github-actions-ci-cd-workflows/)
