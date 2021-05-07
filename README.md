# thanos-pyroscope
Test repo to run Thanos and Prometheus with Pyroscope

It contains:
- Prometheus + Thanos Sidecar
- Thanos Querier with exemplars enabled
- Node exporter
- Tempo
- Pyroscope


## Usage

```
docker-compose up -d
```

Open `localhost:4040` in your browser to view Pyroscope profiles.

![pyroscope](./pyroscope.png)
