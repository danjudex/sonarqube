# SonarQube Compose

## Prerequisites

- Docker and Docker Compose must be installed on your system.

- set vm.max_map_count=262144

```
sudo sh -c "echo 'vm.max_map_count=262144' >> /etc/sysctl.conf && sysctl --system"
```

# Instalation

```
docker compose up -d
```
