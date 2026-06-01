<!-- markdownlint-disable first-line-heading MD041 -->

![header.png](https://raw.githubusercontent.com/shikanime/shikanime/main/assets/github-header.png)

<!-- markdownlint-enable first-line-heading -->

# XQBit

Extra tooling for qBittorrent.

## Tools

### qbittorrent-cleanup

Removes `missingFiles` torrents and resumes recoverable errored torrents.

Configuration is provided via flags or environment variables (prefix `QBT_`):

- `--url` / `QBT_URL`
- `--user` / `QBT_USER`
- `--password` / `QBT_PASSWORD`
- `--timeout` / `QBT_TIMEOUT`

Example:

```bash
go run ./cmd/qbittorrent-cleanup --url https://qbittorrent.example --user alice --password '...'
```

Build image:

```bash
skaffold build
```
