# Helm Exercises

Link to bootcamp section: [Helm Exercises](https://devops-bootcamp.liatr.io/#/5-release-management/5.4.2-helm)

first-helm-chart
---
- Notes on Helm and how to write the `Chart.yaml` file.

Jenkins
---
- This exercise is using the docker container that we made for Jenkins so that we can practice using Helm.
- The health checks are a little bit of an issue. There are two solutions:
	- Do a clean install so you can speed Jenkins along
	- Increase the `initialDelaySeconds`
