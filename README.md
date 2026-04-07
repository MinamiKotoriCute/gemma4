# A simple way to run a local gemma4 model

Start gemma 4 (gemma-4-E2B-it) + open-webui using docker compose

Tested and working on Windows 11 + WSL + 5080

## Requirements:

- NVIDIA graphics card with 16GB+ VRAM

## Prerequisites:

- Install Docker

## Startup Method:

The first startup requires downloading the model, which may take varying times depending on your network speed (approximately 45 minutes for a 500Mbps network with a 5080).

```bash
docker compose up -d
```

## Usage:

Access via browser: http://localhost:3000
