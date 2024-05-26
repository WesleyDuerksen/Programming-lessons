# Requirements
direnv
asdf

# Setup
python -m venv .venv
direnv reload
pip install -r requirements.txt

## Initial project setup instructions
https://mdaverde.com/posts/python-venv-direnv-asdf/
python -m venv .venv
echo "export VIRTUAL_ENV=$PWD/.venv\nexport PATH=$PWD/.venv/bin:\$PATH" > .envrc
direnv allow