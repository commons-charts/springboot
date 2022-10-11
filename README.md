- 更新依赖的
```
helm dependency update
```

- lint

```
helm lint --strict
```

- 模拟测试
```
helm template . | more
```

- package

```
helm package .
```

- 安装app
```
helm upgrade -install springboot springboot-0.1.0.tgz -n default --set Zookeeper.Enabled=true
```