## Dependencies
You will need to install the following dependencies before you can run this application:
`Git
Docker
Docker Compose`



## Windows
To install on Windows open powershell in this directory and type:
```Set-ExecutionPolicy -Scope Process -ExecutionPolicy RemoteSigned```

Then type:
```.\run.ps1```



## *nix (Linux and Mac) 
To install on *nix open a terminal in this directory and type:
`chmod +x run.sh`

Then type:
`./run.sh`


## Configuration
Add a .env file to the root of the project with the following contents:

`TOKEN=<your bot token>`



## How to run

Run the bot with:
```docker-compose up```