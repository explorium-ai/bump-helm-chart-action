# Bump Helm Chart Version

Bump a Helm Chart Version Locally

## Full Example usage

```yaml
- name: Bump a Helm Chart Version Locally
  uses: explorium-ai/bump-helm-chart-action@main
  with:
    chart-path: charts/mychart
    app_version: true
    level: patch
```