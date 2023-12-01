To create a container:
`docker run -p 8888:8888 -v .:/home/jovyan quay.io/jupyter/scipy-notebook:2023-11-17`

Then optionally install and configure LSP: https://github.com/krassowski/jupyterlab-lsp

Running existing:
`docker start -a laughing_ganguly`
