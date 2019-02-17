# Calculator
Calculator Kotlin Spring-Boot api containerized with Docker

# Build
```
gradle clean build bootJar
docker build . -t calculator
```

# Deploy
`docker run -p 3080:8080 calculator`

# Open
http://localhost:3080/calculator/api/