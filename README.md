- 参考
  - https://knowledge.sakura.ad.jp/11633/
  - https://knowledge.sakura.ad.jp/11635/
  - https://github.com/prometheus/prometheus/blob/master/documentation/examples/prometheus.yml
  - https://prometheus.io/docs/prometheus/latest/configuration/recording_rules/

```
vagrant up
docker-compose up -d
```

- http://localhost:9090
- http://localhost:9090/graph?g0.range_input=1m&g0.expr=node_cpu&g0.tab=0
