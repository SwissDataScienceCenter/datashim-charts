# [Datashim](https://github.com/datashim-io/datashim) Helm Chart Repository

This repository checks the [Datashim project](https://github.com/datashim-io/datashim)
once a week for new releases and published the helm charts here over at
https://swissdatasciencecenter.github.io/datashim-charts/.

This repository should be archived when the Datashim helm charts
are officially published.

# Instructions

To add the repository in helm:

```bash
helm repo add datashim https://swissdatasciencecenter.github.io/datashim-charts/
```

To list the available helm charts:

```bash
$ helm search repo datashim 
NAME                    CHART VERSION   APP VERSION     DESCRIPTION                      
datashim/dlf-chart      0.1.0           0.1.0           Dataset Lifecycle Framework chart
```

To install the helm chart :

```bash
helm install datashim datashim/dlf-chart
```