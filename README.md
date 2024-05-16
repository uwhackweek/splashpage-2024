# Combined 2024 Hackweek event page

## Add team members
Here the [instructions to add yourself](team/README.md).

## Build website locally

First create an environment with necessary python packages
```
cd [repository]
mamba env create
mamba activate splashpage
```

Then run the build script
```
./scripts/build_resources.sh
```

And preview your webpage!
```
open _build/html/index.html
```

## Details

This template uses simple text YAML files to fill in key website details.
[Cookiecutter](https://cookiecutter.readthedocs.io/en/stable/README.html) is
then used to populate templated HTML for the final webpage.
