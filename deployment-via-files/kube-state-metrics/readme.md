# kube-state-metrics

## From the prometheus Community:

### https://github.com/prometheus-community/helm-charts/tree/main/charts/kube-state-metrics

1. `helm repo add prometheus-community https://prometheus-community.github.io/helm-charts`
2. `helm repo update`
3. `helm install kube-state-metrics prometheus-community/kube-state-metrics [flags]`

Helm chart consists of the following files to deploy manually.

\*\*\*Note: You have to configure safely as a ton of metrics will be captured if not done properly, Cloud bill will go up! \*\*\*
