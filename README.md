# Clone the repo
git clone https://github.com/your/repo.git
cd repo

# Create and activate virtual environment
uv venv
source .venv/bin/activate  # or .venv\Scripts\activate on Windows

# Sync dependencies
uv sync

# Create data folder to store input spatial data

# Create notebook titled by municipality
e.g. "Worcester.ipynb"