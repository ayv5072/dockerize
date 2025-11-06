# Simple Spring Boot Backend (Student Project)

This is a small backend made with Spring Boot and H2 database. It just runs a basic server.

## How to run
1. Open the folder in IntelliJ or VS Code.
2. Run this in the terminal:
   ```bash
   mvn -q -DskipTests clean package
   java -jar target/backend-1.0.0.jar
   ```
3. Open your browser and go to [http://localhost:8080](http://localhost:8080)

## Run with Docker
```bash
docker build -t backend .
docker run --rm -p 8080:8080 backend
```

Then open http://localhost:8080 again.

That’s it. Just a small working example.
