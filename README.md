# hello-world-api

A simple Go API that responds with "Hello World" on the `/hello` endpoint.

## Getting Started

### Prerequisites

- Go 1.24.11 or higher

### Running the Application

1. Build the application:
```bash
go build -o hello-world-api .
```

2. Run the application:
```bash
./hello-world-api
```

The server will start on port 8080.

### Usage

Make a GET request to the `/hello` endpoint:

```bash
curl http://localhost:8080/hello
```

Response:
```
Hello World
```

### Testing

Run the tests with:

```bash
go test -v
```