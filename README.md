# SG - Utils

## Repository Contents
- Events
- Event Handler
- Event Dispatcher
- RabbitMQ

## Folder Structure
```
sg-utils
├── README.md
├── cmd
│   ├── consumer
│   │   └── main.go
│   └── producer
│       └── main.go
├── docker-compose.yml
├── go.mod
├── go.sum
└── pkg
    ├── events
    │   ├── event_dispatcher.go
    │   ├── event_dispatcher_test.go
    │   └── interfaces.go
    └── rabbitmq
        └── rabbitmq.go

6 directories, 10 files
```