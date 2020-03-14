Для запуска kafka server:
```
[root@otuslinux vagrant]# sudo systemctl start zookeeper
[root@otuslinux vagrant]# sudo systemctl start kafka
```
Restart=on-abnormal выбран поскольку код выхода не равен нулю, соответсвенно нельзя использовать on-failure
