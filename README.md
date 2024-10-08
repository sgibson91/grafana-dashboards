# Grafana Dashboards for JupyterHub

[![Documentation build status](https://img.shields.io/readthedocs/jupyterhub-grafana?logo=read-the-docs)](https://jupyterhub-grafana.readthedocs.org/en/latest/)

Grafana Dashboards for use with [Zero to JupyterHub on Kubernetes](http://z2jh.jupyter.org/)

![Grafana Dasboard Screencast](demo.gif)

## What?

Grafana dashboards displaying prometheus metrics are *extremely* useful in diagnosing
issues on Kubernetes clusters running JupyterHub. However, everyone has to build their
own dashboards - there isn't an easy way to standardize them across many clusters run
by many entities.

This project provides some standard [Grafana Dashboards as Code](https://grafana.com/blog/2020/02/26/how-to-configure-grafana-as-code/)
to help with this. It uses [jsonnet](https://jsonnet.org/) and
[grafonnet](https://github.com/grafana/grafonnet-lib) to generate dashboards completely
via code. This can then be deployed on any Grafana instance!

## Deployment

Deployment instructions are available in [the documentation site](https://jupyterhub-grafana.readthedocs.io/en/latest/tutorials/deploy.html).
