# About

Simple quickstart google cloud message server using go programming language / golang

## Setup

Before starting replace the "google-service-key.json" to correct path private key file in main.go

```go
// REPLACE "google-service-key.json" to correct path private key file
// visit https://firebase.google.com/docs/cloud-messaging/auth-server#provide-credentials-manually
opt := option.WithCredentialsFile("google-service-key.json")
```

## Run / Build

Run

```bash
go run main.go
```

Build

```bash
go build main.go
```

## Docs

 [Google cloud message documentation](https://firebase.google.com/docs/cloud-messaging/).
