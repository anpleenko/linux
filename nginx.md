При ошибке 

```
nginx: [emerg] bind() to 0.0.0.0:7777 failed (98: Address already in use)
```

запускаем комманду 

```
netstat -tnlp | grep ${номер порта}
```
