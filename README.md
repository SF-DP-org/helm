app helm chart
==============

Description
-----------

This repository contains a helm chart, includes services and deployment manifests and variables, divided by files by services.

Usage
-----

    helm upgrade --install django-app . --values ./values-app.yml --values ./values-db.yml
