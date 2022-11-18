.. _index:

Welcome to Bivalent Data Technology
=============================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:

About Bivalent Data Technology
==================

Bivalent Data Technology is a DevOps B2B consultancy company based in Romania

TLDR: Do you need ?

 - Opensource
 - Backup and restore Docker containers or k8s pods (MySQL, Files)
 - Custom SQL Metrics (YAML defined custom SQL queries exposing Prometheus metrics)
 - https://github.com/valiDM/bivalent-web
 - https://hub.docker.com/r/validm/bivalent-web


Installation
==================

Kubernetes Operator
- https://github.com/valiDM/bivalent-web
- Install the operator via HELM chart and use CRDs in convinient way

HELM installation
- https://github.com/valiDM/bivalent-web
- There is a HELM chart in conveior repo. Just run it as you would normally do.
- The chart will be soon uploaded to global helm registry

Standard Kubernetes installation
- https://github.com/valiDM/bivalent-web
- There are static Kubernetes manifests that will deploy conveior into daemon sets.
- Also it will create ServiceMonitor that will be scraped by Prometheus.

Docker installation
- https://github.com/valiDM/bivalent-web
- In directory conveior-docker there is docker-compose file and bash file to help you installing conveior on your docker server.


Contact
==================

 - E-mail: 
