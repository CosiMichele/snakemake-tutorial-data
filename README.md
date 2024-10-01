[![Gitpod Ready-to-Code](https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod)](https://github.com/CosiMichele/snakemake-tutorial-data)

# Example data for the Snakemake tutorial

This repository hosts the data needed for the [Snakemake tutorial](https://snakemake.readthedocs.io/en/stable/tutorial/tutorial.html).

## Execution

1. Test workflow with `snakemake -n`
2. Create a [Directed Acyclic Graph (DAG)](https://en.wikipedia.org/wiki/Directed_acyclic_graph) image with `snakemake --dag | dot -Tsvg > dag.svg`
3. Execute workflow with `snakemake --cores 1`
