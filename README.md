# Ansible Role: redis

## Description

Manage redis-server - Persistent key-value database.

## Requirements

None

## Dependencies

None

## OS Platforms

- Ubuntu 20.04 focal
- Ubuntu 22.04 jammy

## Example Playbook

```
- hosts: all
  roles:
    - redis
```

## Role Variables

### redis_debug: (bool)

```
redis_debug: false
```

### redis_package_ensure: (string)

```
redis_package_ensure: 'present'
```

### redis_service_ensure: (string)

```
redis_service_ensure: 'started'
```

### redis_service_enable: (bool)

```
redis_service_enable: true
```

### redis_daemon_config_options: (dict)

```
redis_daemon_config_options: {}
```

### redis_server_config_options: (dict)

```
redis_server_config_options: {}
```
