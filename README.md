## Logging and monitoring system of Docker containers

`daemon.json`

```json
{
    "log-driver": "loki",
    "log-opts": {
        "loki-url": "http://localhost:3100/loki/api/v1/push",
        "loki-batch-size": "400",
        "mode": "non-blocking"
    }
}
```
