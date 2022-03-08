## Start Service

```bash
dc up -d kong db fluentd
```

### With Environment Variables

```bash
export $(cat .env | xargs) && dc up -d kong db fluentd
```