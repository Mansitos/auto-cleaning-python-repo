# Auto Cleaning and Formatting python repo
[![Automatic Code Cleaning & Formatter](https://github.com/Mansitos/auto-cleaning-python-repo/actions/workflows/code-cleaner.yml/badge.svg)](https://github.com/Mansitos/auto-cleaning-python-repo/actions/workflows/code-cleaner.yml)

This repo contains multiple CI/CD GitHub Action-based workflow tests to keep python repositories clean and high quality

After any push:
- A 'code-cleaner' GitHub action runs automatically
- It performs various cleaning and formatting steps
- Automatically push the files affected by those steps

List of performed steps (in-order of execution):

## 1. Cleaning Notebook (.ipynb) Outputs 🧼
This way, the notebooks are always clean and the output cells are not included!
- Cleaning is performed via [nbconvert library](https://github.com/jupyter/nbconvert)

## 2. Auto Formatting in PEP8 🏗️
Any python file is modified and made PEP8-compliant!
- It uses the [autoyapf open-source library](https://github.com/marketplace/actions/autoyapf)
- ❌ TODO: Doesn't work on ipynb python cells!?!
- ❌ TODO: Let it run on all notebooks in the repo

---

### How to test:
- Modify or create a python script (not compliant with PEP8) and run the notebook to produce some outputs
- Push
- Wait for GitHub action to run
- Look at your beautiful quality code 🍃




