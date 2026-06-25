# Multi Stage Dockerfile

## Project
Simple Node.js application demonstrating:

- Single Stage Dockerfile
- Multi Stage Dockerfile

## Build Single Stage

docker build -t single -f Dockerfile .

## Run

docker run -p 3000:3000 single

## Build Multi Stage

docker build -t multi -f Dockerfile2 .

## Run

docker run -p 3000:3000 multi
