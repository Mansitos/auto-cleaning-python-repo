# GitHubActions Tests...

### Auto Formatting in PEP8
This repo has a github action that automatically formats any python script in PEP8.
- The github action 'pep8-formatter' runs after any push
- It uses the [autoyapf open-source library](https://github.com/marketplace/actions/autoyapf) to modify .py files according to PEP8 guidelines
- The GitHub Action (if does not fail) apply changes by automatically executing a new commit/push with formatted files

#### How to test:
- Modify or create a python script (not compliant with PEP8)
- Push
- Wait for GitHub action to run
- Look at your beautiful code 🍃


