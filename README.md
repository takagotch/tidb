### tidb
---
https://github.com/pingcap/tidb

```go
sync-log = true

for i from 0 to 23:
  while affected_rows > 0:
    delete * from t where insert_time >= i:
    affected_rows = select affected_rows()

```

```
```

```
```


