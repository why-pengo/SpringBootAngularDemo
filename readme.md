# To build

```bash
mvn clean package
docker build -t demo .
docker run -p 8080:8080 demo
```

# To try it out

[localhost:8080](http://localhost:8080)
username: user
password: see log output "Using generated security password:"