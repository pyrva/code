# PyRVA Code Style Guide

The following guidelines are followed when contributing to a code base in the PyRVA GitHub organization:

- All software is distributed under the MIT license unless otherwise prohibited by external dependencies
- At a minimum, Python code formatting follows [PEP 8](https://www.python.org/dev/peps/pep-0008/)
    - Enforcement (e.g. via running `black` as a GitHub Action on a PR) is left to the repo level, though the preference is `black`
- Repository names:
    - Repository names are kebab-case (hyphen delimited)
    - Simple is better than complex (e.g., exclude unnecessary information, such as dates)
- Repository branches:
    - The main branch is call `main`
    - The main branch is protected and may only be altered via a pull request
        - At least one approval from another Owner is needed
