Run: bash bootstrap.sh
---
Run: kubectl get nodes -o jsonpath="{range .items[*]}{.metadata.name} {.spec.taints[]}{\"\n\"}"
---
Run: kubectl get nodes --show-labels