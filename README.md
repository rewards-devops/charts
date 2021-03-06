# charts

[Github Source Code](https://github.com/rewards-devops/charts)

Public Helm chart repository - Rakuten Rewards Devops

_Notes_: The chart only hosts

- deprecated helm chart. For example `kube2iam`
- helm charts that no longer being maintained by the community.

Those charts are still being used and maintained by Rewards Platform team.

## Publish a chart

- Create your feature branch from `master`

```sh
git clone https://github.com/rewards-devops/charts.git
git checkout -b <feature_branch_name>
```

- Push new charts to `charts/` folder.
- Create PR to `master` branch
- Review and merge PR
- Github Actions workflow automatically detect the chart's version and release the chart.

## Usage

Example to install `metrics-server`

```sh
helm repo add rr-charts https://rewards-devops.github.io/charts
helm install metrics-server rr-charts/metrics-server
```
