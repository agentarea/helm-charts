# AgentArea Helm Charts

Public Helm chart repository for AgentArea.

## Usage

```bash
helm repo add agentarea https://agentarea.github.io/helm-charts
helm repo update
helm search repo agentarea
helm install agentarea agentarea/agentarea
```

## Artifact Hub Verification

This repository includes Artifact Hub verification metadata at `artifacthub-repo.yml`.

## Index and Releases

- Chart packages (`*.tgz`) are stored in this repository.
- `index.yaml` is generated and updated on every release.
- Served via GitHub Pages at `https://agentarea.github.io/helm-charts`.

## Publishing (CI from agentarea/agentarea)

- The main repo CI packages charts and pushes here using a GitHub App token.
- It merges the existing `index.yaml` to preserve history.

