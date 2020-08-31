#### 删除存储池

```
ceph tell mon.* injectargs --mon-allow-pool-delete=true
ceph osd pool delete   k8s-data k8s-data --yes-i-really-really-mean-it
```
