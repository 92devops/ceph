#### feature set mismatch

报错：` rbd: map failed exit status 110, rbd output: rbd: sysfs write failed`
解决办法：`$ ceph osd crush tunables legacy`
