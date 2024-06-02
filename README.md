## Setup Go Repo
go mod init gihub.com/Jating73/go-todo-app

## Install Fiber Framework inspired by Express.js, which makes it straightforward to build web applications.
go get github.com/gofiber/fiber/v2

## Run a server
go run main.go

## Install Package to restart server when new changes comes
go install github.com/cosmtrek/air@latest

## Create a configuration file to use "air" in air.toml file
Use Chatgpt to create a file for that 

## Run server using air
air

## Install Dotenv to use env variables
go get github.com/joho/godotenv

## Install Mongodb to use mongo in our app
go get go.mongodb.org/mongo-driver/mongo