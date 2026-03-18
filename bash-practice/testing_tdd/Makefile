.PHONY: create-structure test-pytest


create-structure:
    mkdir -p src docs tests
    touch docs/DOMAIN.md
    touch src/.gitkeep
    touch tests/.gitkeep
    touch requirements.txt
    touch setup.py
    touch README.md

install-dep:
	pip install -r requirements

install:
	pip install -e .

test-pytest:
    pytest

test: install-dep install test-pytest