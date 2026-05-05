## 👋 Welcome to crafty 🚀

Powerful game server management panel

## 📋 Description

Powerful game server management panel

## 🚀 Services

- **crafty**: registry.gitlab.com/crafty-controller/crafty-4:latest

## 📦 Installation

### Option 1: Quick Install
```bash
curl -q -LSsf "https://raw.githubusercontent.com/composemgr/crafty/main/docker-compose.yaml" -o compose.yml
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

## 🔧 Configuration

### Environment Variables

```shell
TZ=America/New_York
```

See `docker-compose.yaml` for complete list of configurable options.

## 🌐 Access

- **Web Interface**: http://172.17.0.1:8096

## 📂 Volumes

- `./volumes/config/crafty` - Data storage
- `./volumes/data/crafty` - Data storage

## 🔍 Logging

```shell
docker compose logs -f crafty
```

## 🛠️ Management

```bash
# Start services
docker compose up -d

# Stop services
docker compose down

# Update to latest images
docker compose pull && docker compose up -d

# View logs
docker compose logs -f

# Restart services
docker compose restart
```

## 📋 Requirements

- Docker Engine 20.10+
- Docker Compose V2+

## 🤝 Author

🤖 casjay: [Github](https://github.com/casjay) 🤖  
🦄 composemgr: [Github](https://github.com/composemgr) 🦄
