
.. image:: https://img.shields.io/badge/python-3.7-blue
   :class: badge

Client for submitting Owl pipelines to a remote cluster running Dask on Kubernetes.

Owl is a framework for submitting jobs (a.k.a. pipelines) in a remote cluster.
The Owl server runs jobs in Kubernetes using Dask. The Owl client authenticates
with the remote server and submits the jobs as specified in a pipeline
definition file.
