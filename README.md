- 参考
  - https://knowledge.sakura.ad.jp/11633/
  - https://github.com/prometheus/prometheus/blob/master/documentation/examples/prometheus.yml

```
vagrant up
docker-compose up -d
```

- http://localhost:9090
- http://localhost:9090/graph?g0.range_input=1h&g0.expr=node_memory_Active&g0.tab=0
