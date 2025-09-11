# Helm Charts Repository

This repository hosts Helm charts for various projects.

## Available Charts

- `peerbot` - Kubernetes deployment chart for Peerbot Slack bot

## Usage

```bash
helm repo add peerbot https://buremba.github.io/helm-charts/
helm repo update
helm search repo peerbot
helm install my-peerbot peerbot/peerbot
```

## Repository Structure

- Chart packages (.tgz files) are in the root directory
- `index.yaml` contains the repository index
- Source charts are maintained in their respective private repositories

## License

See individual chart licenses.
