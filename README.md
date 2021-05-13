# README

The benchmark on the notebook with suffix 2021-05-13 was run on a `n2-standard-4` instance on GCP.

# Environment
In order to run the benchmark you need to create the given environment using the following commands.

```bash
conda env create -f env.yaml
source activate pandas_benchmark
python -m ipykernel install --user --name pandas_benchmark --display-name pandas_benchmark
```
