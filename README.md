# eWaterCycle Python BMI example: a leaky bucket model

This repository is a template for creating a new hydrological model in Python, using the Basic Model Interface (BMI).

The goal is to plug this model into eWaterCycle, and as such forcing data and configuration file handling will be performed using eWaterCycle.


## Installation
Install this package alongside your prefered Python environment.

```console
pip install -e .
```

To be able to run the notebooks, this has to be an environment with `ewatercycle` already installed.

## Implementing your own model

To implement your own model, use the `LumpedBmiTemplate` as a starting point. You can use the LeakyBucket BMI implementation as an example.

## License

`ewatercycle-plugin` is distributed under the terms of the [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html) license.
