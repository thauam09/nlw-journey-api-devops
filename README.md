# nlw-journey-go

- Tecnologia: Go
- Versão: 1.22.2
- Porta: 8080

### Postgres

## Preparação Dev

- Preparação:
  - Instalar libs: `go mod download && go mod verify`
- Execução:
  - Executar aplicação em modo dev: `go run cmd/journey/journey.go`
  - Orquestração local: `docker compose up --build -d`

## Preparação Prod - Dockerfile

- Preparação:
  - Instalar libs: `go mod download && go mod verify`
  - Buildar projeto: `go build -o /bin/journey ./cmd/journey/journey.go`
- Execução:
  - Executar aplicação em modo prod: `./journey` (executa binário)
