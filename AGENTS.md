# AGENTS.md

This repository contains extra tooling for qBittorrent.

## Build / Test Commands

- Run checks:
  - `go test ./...`
- Run qbittorrent-cleanup:
  - `go run ./cmd/qbittorrent-cleanup --help`

## Repository Layout

- `cmd/`: CLI entrypoints
  - `cmd/qbittorrent-cleanup/`: manages errored torrents in qBittorrent
