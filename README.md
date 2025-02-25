## Setting up a project with this template

1. Rename the `/template` directory to your project name. This name will also be the name of the Python package generated by this template.
2. Find and replace (Ctrl + Shift + R in most editors) `<TEMPLATE:project_title>` (should be the same as the project name from step 1), `<TEMPLATE:repository_name>`, `<TEMPLATE:project_description>`, `<TEMPLATE:author_name>` and `<TEMPLATE:author_email>` across this project. This will replace these strings in `pyproject.toml`, `README.md`, `mkdocs.yml`, `docs/index.md`.
3. (Optional) Configure a runner for your project via `Settings > CI/CD` on GitLab, and update the `.gitlab-ci.yml` file by uncommenting the stages you want.
4. (Optional) Install pre-commit hooks by running `pre-commit install` in the project root.
5. Delete this section of the README.

---

# <TEMPLATE:project_title>

_Built with Poetry 2.0.1 and Python 3.11_

<TEMPLATE:project_description>

## 📦 Installation

You can install **<TEMPLATE:project_title>** using **Poetry**:

1. Clone the repository:
    ```sh
    git clone
    cd <TEMPLATE:repository_name>
    ```
2. Install with Poetry (use `--dev` to install development dependencies):
    ```sh
    poetry install --with dev
    ```
3. Run the tests:
    ```sh
    poetry run pytest
    ```
