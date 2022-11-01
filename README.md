# information-bias-bench
A benchmark for evaluating Information bias

This repository contains files for evaluating information bias based on DBpedia Entity benchmark.

The following files are available in this repository.

- `.run` - filex ending with `.run` contain the evaluated runs with top `1000` results for each dataset query.
- `.qrels` - containg the automatic evaluation based on the `.run` file assigning `2` for entities with `100%` likelihood and `1` otherwise.


We refer to Trec Eval tool for metrics evaluation.
