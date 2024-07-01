## Logging and monitoring system of Docker containers

`deamon.json`

```json
{
    "debug": true,
    "log-driver": "loki",
    "log-opts": {
        "loki-url": "http://localhost:3100/loki/api/v1/push",
        "loki-batch-size": "400"
    }
}
```
