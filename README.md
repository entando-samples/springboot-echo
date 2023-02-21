```mvn clean package```

```docker build -t <your-docker-organization>/springboot-echo:0.0.1-SNAPSHOT .```

```docker run --rm -p 8080:8080 -e GREETING_NAME="my Name" <your-docker-organization>/springboot-echo:0.0.1-SNAPSHOT```

```docker push <your-docker-organization>/springboot-echo:0.0.1-SNAPSHOT```
