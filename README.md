# vss-lab

## Local setup

1. Install [`uv`](https://docs.astral.sh/uv/getting-started/installation/):
   ```bash
   curl -LsSf https://astral.sh/uv/install.sh | sh
   ```
2. Install dependencies:
   ```bash
   uv sync
   ```
3. Open the repo in VS Code and install the recommended extensions:
   - [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
   - [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)
4. Open `lab_student.ipynb` and select the `.venv` kernel (created by `uv sync`) to run the notebook.
