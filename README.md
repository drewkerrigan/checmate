# Checmate Benchmarking

# Checmate vs Docker

### Test Details:

Parameter | Value
--- | --- | ---
*Duration* | `1 minute`
*Concurrency | `3 Erlang workers`
*Key space(Redis)* | `1000000 keys`
*Value size(Redis)* | `1000 bytes`
*Operations* | `GET`

### Checmate Throughput (ops/sec)

![checkmate gets](checkmate.png)

### Docker Throughput (ops/sec)

![docker gets](docker.png)