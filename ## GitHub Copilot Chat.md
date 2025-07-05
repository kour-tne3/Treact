## GitHub Copilot Chat

- Extension Version: 0.22.4 (prod)
- VS Code: vscode/1.95.3
- OS: Mac

## Network

User Settings:
```json
  "github.copilot.advanced": {
    "debug.useElectronFetcher": true,
    "debug.useNodeFetcher": false
  }
```

Connecting to https://api.github.com:
- DNS ipv4 Lookup: 140.82.112.6 (47 ms)
- DNS ipv6 Lookup: ::ffff:140.82.112.6 (43 ms)
- Electron Fetcher (configured): HTTP 200 (353 ms)
- Node Fetcher: HTTP 200 (149 ms)
- Helix Fetcher: HTTP 200 (391 ms)

Connecting to https://api.individual.githubcopilot.com/_ping:
- DNS ipv4 Lookup: 140.82.112.22 (28 ms)
- DNS ipv6 Lookup: ::ffff:140.82.112.22 (30 ms)
- Electron Fetcher (configured): HTTP 200 (55 ms)
- Node Fetcher: HTTP 200 (274 ms)
- Helix Fetcher: HTTP 200 (179 ms)

## Documentation

In corporate networks: [Troubleshooting firewall settings for GitHub Copilot](https://docs.github.com/en/copilot/troubleshooting-github-copilot/troubleshooting-firewall-settings-for-github-copilot).