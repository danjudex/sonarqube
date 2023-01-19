# Requirements

- set vm.max_map_count=262144

```
sudo echo 'vm.max_map_count=262144' >> /etc/sysctl.conf && sudo sysctl --system
```

# Instalation

```
docker compose up -d
```
