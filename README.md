# Test JupyterDask Image Apptainer

Create a custom image to run Jupyter and Dask using Apptainer and GitHub Actions.

Start Jupyter using:
```shell
apptainer exec \
  oras://ghcr.io/fnattino/test-jupyterdask-image-apptainer:latest \
  jupyter lab --no-browser --port=8888 --ip=0.0.0.0
```
