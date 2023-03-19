# Development
Setup of the environment currently uses Nix and direnv to install Python, pip, and virtualenv. The virtualenv is then used to install `molecule`, `yamllint`, `ansible-lint`, and `ansible-core`, among other dependencies. Steps to set up the environment:
1. Clone the repo to your local machine.
1. With Nix and direnv installed, run `direnv allow`. This will set up the Python environment.
1. Create a new virtual environment with `python3 -m venv .venv`
1. Activate the virtual environment with `source .venv/bin/activate`
1. Install needed dependencies with `python3 -m pip install -r requirements.txt`
