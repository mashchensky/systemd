Для запуска kafka server:
```
[root@otuslinux vagrant]# sudo systemctl start kafka
```
Restart=on-failure выбран поскольку код выхода 143 добавлен в успешные соответственно он не будет учитываться как ошибочный.
