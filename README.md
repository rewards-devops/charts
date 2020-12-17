# charts

## Publish a chart

- push new charts to `charts/` folder. 
- workflow automatically detect the chart version and release the chart

## Usage

```sh
helm repo add rr-charts https://rewards-devops.github.io/charts
helm install metrics-server rr-charts/metrics-server
```
