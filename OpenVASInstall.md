# OpenVAS Install
### _Report by Noah Ralston_

This report is designed to show how I installed OpenVAS onto a Ubuntu based system.

## Step 0: Docker
Though this is not a required portion of this report, I believe understanding how to install docker could be beneficial to me in the future, so I'm putting it here anyways

1. Install Ubuntu Linux on a VM or onto specific hardware (skipping most of these steps because it is very simple)
2. Navigate to the terminal and use these commands
```sh
sudo apt update
sudo apt install docker.io
```
3. Start the docker daemon by running the command
```sh
sudo systemctl start docker
```
4. Install the docker compose plugin by running
```sh
sudo apt install docker-compose-plugin
```
5. Test by finding the compose version
```sh
docker compose version
```
Now you have installed docker and are ready to install OpenVAS

## Step 1: