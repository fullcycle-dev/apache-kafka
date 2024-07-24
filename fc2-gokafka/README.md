# Go e Apache Kafka

[voltar](../README.md)

### 1 - Preparando ambiente para implementação

```sh
$ docker-compose up
```

### 2 - Setando ambiente Go

```sh
$ docker exec -it gokafka bash
root@114633133f16:/go/src#
```

```sh
$ root@114633133f16:/go/src# ls
Dockerfile  README.md  docker-compose.yaml
```

```sh
$ root@114633133f16:/go/src# go mod init github.com/fullcycle-dev/apache-kafka/tree/main/fc2-gokafka
go: creating new go.mod: module github.com/fullcycle-dev/apache-kafka/tree/main/fc2-gokafka
```

```sh
$ root@114633133f16:/go/src# go run cmd/producer/main.go
Hello Go
```

[voltar](../README.md)
