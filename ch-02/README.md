## Setup (Docker)
```
$ git clone https://github.com/meistiyak/devops.git
$ cd devops/ch-02/
$ docker build -t devops-ch-02 .
$ docker run -d -p 88:80 devops-ch-02
```

## Check in browser
```
$ localhost:88
```

## Docker Basic Commends:
```
$ docker pull image_name 		[Pull Docker Image from docker file]
$ docker -ps -a  			[to check docker container]
$ docer rm id/name 			[Remove docker container]
$ docer rm -vf $(docker ps -a -q) 	[To Remove all docker container at a time]
$ docker exec -it id/name sh		[Loging into a container]
$ docker start id/name 			[To start docker container]
$ docker stop id/name 			[To stop docker container]
```