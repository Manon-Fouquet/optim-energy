# LP in energy systems

A Linear Programming (LP) implementation of a simple energy system with:

- 1 Battery Energy Storage System (BESS)
- 1 PV field
- grid connection
- local load

The model is implemented with the [pyomo](http://www.pyomo.org/) optimization framework.

The following options are available:

- no export to the grid
- no import from the grid
- no load shedding allowed

## Quick setup

Poetry is used to manage dependencies. Once installed run:

```
poetry install
```

Then run python notebook.

