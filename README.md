# mygRPC_app

## How to operate docker
### setup
1. Install with : `https://github.com/iamtatsuki05/mygRPC_app.git`
### docker configuration
1. `docker compose up -d --build`
### Connect to and disconnect from docker
1. connect : `docker compose exec <service> bash`
2. disconect : `exit`
### Starting and Stopping Containers
1. Starting : `docker compose start`
2. Stopping : `docker compose stop`

## How to Use App
Please Open `http://localhost:3000/`

## Directory structure
```text
./
├── .dockerignore
├── .git
├── .gitattributes
├── .github
├── .gitignore
├── Makefile
├── README.md
├── backend                      <- NodeJs, Golang, Python gRPC apps
├── compose.yaml
├── docs
├── env.sample
└── frontend                     <- React base Web
```
