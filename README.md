# [Learning Dapr](https://www.oreilly.com/library/view/learning-dapr/9781492072416/)
## Building Distributed Cloud Native Applications 
### By Haishi Bai & Yaron Schneider

---

## Errata

`--port` seems to be replaced by `--dapr-http-port` so when the book suggests:

    dapr run --app-id hello-dapr --app-port 8088 --port 8089 go run main.go

Instead you need to apply

    dapr run --app-id hello-dapr --app-port 8088 --dapr-http-port 8089 go run main.go
