[![img](https://img.shields.io/github/contributors/MArpogaus/python-project-skeleton.svg?style=flat-square)](https://github.com/MArpogaus/python-project-skeleton/graphs/contributors)
[![img](https://img.shields.io/github/forks/MArpogaus/python-project-skeleton.svg?style=flat-square)](https://github.com/MArpogaus/python-project-skeleton/network/members)
[![img](https://img.shields.io/github/stars/MArpogaus/python-project-skeleton.svg?style=flat-square)](https://github.com/MArpogaus/python-project-skeleton/stargazers)
[![img](https://img.shields.io/github/issues/MArpogaus/python-project-skeleton.svg?style=flat-square)](https://github.com/MArpogaus/python-project-skeleton/issues)
[![img](https://img.shields.io/github/license/MArpogaus/python-project-skeleton.svg?style=flat-square)](https://github.com/MArpogaus/python-project-skeleton/blob/main/LICENSE)
[![img](https://img.shields.io/github/actions/workflow/status/MArpogaus/python-project-skeleton/test.yaml.svg?label=test&style=flat-square)](https://github.com/MArpogaus/python-project-skeleton/actions/workflows/test.yaml)
[![img](https://img.shields.io/github/actions/workflow/status/MArpogaus/python-project-skeleton/release.yaml.svg?label=release&style=flat-square)](https://github.com/MArpogaus/python-project-skeleton/actions/workflows/release.yaml)
[![img](https://img.shields.io/badge/pre--commit-enabled-brightgreen.svg?logo=pre-commit&style=flat-square)](https://github.com/MArpogaus/python-project-skeleton/blob/main/.pre-commit-config.yaml)
[![img](https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555)](https://linkedin.com/in/MArpogaus)

[![img](https://img.shields.io/pypi/v/minimal-python-project-skeleton.svg?style=flat-square)](https://pypi.org/project/minimal-python-project-skeleton)


# Minimal Python Project Skeleton

1.  [About The Project](#org1b5ca0b)
2.  [Getting Started](#org915b25a)
    1.  [Installation](#orgf73ca0a)
3.  [Contributing](#orgcae31e8)
4.  [License](#org236d2b4)
5.  [Contact](#org901b7c6)
6.  [Acknowledgments](#org935ff24)


<a id="org1b5ca0b"></a>

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
    │   └── __init__.py
    └── test
        └── test_func.py

    5 directories, 12 files

It contains just the minimum to get you started with a ready configured GitHub actions for automated [linting](<https://github.com/MArpogaus/minimal-python-project-skeleton/blob/main/.github/workflows/pre-commit.yaml>), [testing](<https://github.com/MArpogaus/minimal-python-project-skeleton/blob/main/.github/workflows/test.yaml>), and [releasing](<https://github.com/MArpogaus/minimal-python-project-skeleton/blob/main/.github/workflows/release.yaml>) on PiPy.


<a id="org915b25a"></a>

## Getting Started

Use this template directly to [create a new GitHub repository](<https://github.com/new?template_name=minimal-python-project-skeleton&template_owner=MArpogaus>) or just clone the repository to your desired destination and start working on your new project.

**Pro-Tipp:** If you later want to update the template, keep a separate branch (i.e. `skeleton`) around and `cherry-pick` the changes you would like to keep for future projects.
This way you can also pull the latest version from upstream and `checkout` the new files you would like to use in your project.


<a id="orgf73ca0a"></a>

### Installation

This package is available on [PyPI](https://pypi.org/project/minimal-python-project-skeleton/). You install it using pip:

    pip install minimal_python_project_skeleton


<a id="orgcae31e8"></a>

## Contributing

Any Contributions are greatly appreciated! If you have a question, an issue or would like to contribute, please read our [contributing guidelines](CONTRIBUTING.md).


<a id="org236d2b4"></a>

## License

Distributed under the [MIT License](LICENSE)


<a id="org901b7c6"></a>

## Contact

[Marcel Arpogaus](https://github.com/MArpogaus/) - [znepry.necbtnhf@tznvy.pbz](mailto:znepry.necbtnhf@tznvy.pbz) (encrypted with [ROT13](<https://rot13.com/>))

Project Link:
<https://github.com/MArpogaus/python-project-skeleton>


<a id="org935ff24"></a>

## Acknowledgments

-   README inspired by [othneildrew/Best-README-Template](https://github.com/othneildrew/Best-README-Template)
-   Contribution guidelines inspired by [probabilists/zuko](https://github.com/probabilists/zuko/)
-   Release workflow inspired by [packaging.python.org](https://packaging.python.org/en/latest/guides/publishing-package-distribution-releases-using-github-actions-ci-cd-workflows/)
