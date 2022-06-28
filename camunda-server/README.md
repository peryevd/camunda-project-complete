## Install:
- download from:
 ```https://camunda.com/download/```
- unpack anywhere

### Run:
``` ./start.sh```

free 8080 port required

### Stop:
``` ./shutdown.sh```

### Setting CORS for excamad:
- go to  ```configuration/default.yml```
- change  

``` 
run:
    cors:
      enabled: true
    example:
      enabled: true
```
- to
``` 
run:
    cors:
      enabled: true
      allowed-origins: "excamad url"
      allow-credentials: "true"
    example:
      enabled: true
```