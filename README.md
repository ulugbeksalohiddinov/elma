[pv.txt](https://github.com/user-attachments/files/18286072/pv.txt)root@node1:/home/user/mkb# cat pv.yaml

   [UploaapiVersion: v1
kind: PersistentVolume
metadata:
  name: task-pv-volume
  labels:
    type: local
spec:
  storageClassName: manual
  capacity:
    storage: 8Gi
  accessModes:
    - ReadWriteOnce
  hostPath:
    path: "/mnt/data"
ding pv.txt…]()

