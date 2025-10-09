# Syndirella

Syndirella is found at https://github.com/oxpig/syndirella where more documentation and examples are found.


### System Requirements

See https://github.com/oxpig/syndirella/blob/75a60b2309e022827a9e0fead945995ac00fff26/pyproject.toml for dependencies.

Operating systems tested on: Mac OS 14.6.1 (23G93), x86_64 GNU/Linux

### Installation

```bash
conda create -n syndirella python=3.10
conda activate syndirella
pip install cgrtools --use-pep517
pip install syndirella

syndirella setup-aizynth # Will install large model files (~750MB total) to [syndirella_package_path]/aizynth/
```

Install time: ~10 mins

### Demo

See [run_example.ipynb](run_example.ipynb) to run an elaboration for the D2R-12 scaffold and viewing the output.

