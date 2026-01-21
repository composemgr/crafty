# Crafty

A self-hosted crafty application.

## Installation

### Option 1: Quick Install
```bash
curl -q -LSsf "https://raw.githubusercontent.com/composemgr/crafty/main/docker-compose.yaml" | docker compose -f - up -d
```

### Option 2: Git Clone
```bash
git clone "https://github.com/composemgr/crafty" ~/.local/srv/docker/crafty
cd ~/.local/srv/docker/crafty
docker compose up -d
```

### Option 3: Using composemgr
```bash
composemgr install crafty
```

## Configuration

See docker-compose.yaml for environment variables and configuration options.

## Documentation

Check the official project documentation for detailed setup and usage information.
