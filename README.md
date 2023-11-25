![Read the Docs](https://img.shields.io/readthedocs/frc-atlas-site)
![GitHub Workflow Status (with event)](https://img.shields.io/github/actions/workflow/status/frcatlas/frc-atlas-site/ci.yml)

# FRC Atlas
### Dependencies
- Install pip dependencies with `pip install -r source/requirements.txt`
- To update dependencies, we use poetry. After any poetry changes, run `poetry export -f requirements.txt --output source/requirements.txt --without-hashes` to update the requirements.txt file.

### Local Development
- Run `sphinx-autobuild source build` to start a local server that will automatically rebuild the site when changes are made.

## License
Copyright © 2023, FRC Atlas Contributors. Some rights reserved. This work is licensed
under the terms of the Creative Commons Attribution 4.0 International License which
can be found in the root directory of this project.
