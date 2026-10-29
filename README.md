# TriggerRepoB

Holds `content.txt`, which AppPipelineRepo renders onto a web page.

Pushing to `main` does **not** deploy. Pushing a tag matching `v*` does:

```bash
git tag v1.0.1 && git push origin v1.0.1
```
