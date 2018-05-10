### tutorial: https://ewanvalentine.io/microservices-in-golang-part-1/
### part 1
- make proto
    - $ cd consignment-service/ && make build 
- go run consignment-service/main.gp
- go run consignment-cli/cli.go

`docker-compose build vessel-service consignment-service`
`docker-compose run vessel-service consignment-service`
`cd consignment-cli && make build && make run`

or 

`docker-compose up`