# Spring4Shell
### spring4shell POC

## Vulnerable docker 
```sh
docker run -p 9090:8080 vulfocus/spring-core-rce-2022-03-29
```

## Running the exploit
```sh
python3 exploit.py --url http://localhost:9090
```

![spring4shell](spring4shell.png)
