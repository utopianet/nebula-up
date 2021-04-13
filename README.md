# Nebula-Up

`Nebula-Up` is an utitly PoC to enable developer and user to bootstrap an nebula-graph cluster with nebula-graph-studio(Web UI) and nebula-graph-console(Command UI) ready out of box in oneliner install.

Also, it's optimized to leverage China Repo Mirrors(docker, brew, gitee, etc...) in case needed enable a smooth deployment for Mainland China users.

With Shell:

```bash
curl -fsSL https://github.com/wey-gu/nebula-up/raw/main/install.sh | sh
```
With PowerShell:
```powershell
iwr https://github.com/wey-gu/nebula-up/raw/main/install.ps1 -useb | iex
```

TBD:
- [ ] Fully optimized for CN users
- [ ] With version specification support
- [ ] Packaging into homebrew/chocolatey?

