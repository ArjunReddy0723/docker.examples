### Difference between Docker on Linux and Docker on Mac/Windows environments
Based on your OS, your DOCKER_HOST is different. On Linux, it will simply be your localhost. For Mac/Windows, you should obtain the appropriate IP using the following command:
```
docker-machine ip default
```

For example, Selenium hub on Mac
```
http://192.168.99.100:4545/grid/console
```

Selenium hub on Linux
```
http://localhost:4545/grid/console
```
