## Setup (Docker)
```
$ git clone https://github.com/meistiyak/devops.git
$ cd devops/ch-02/
$ docker build -t devops-ch-02 .
$ docker run -d -p 88:80 devops-ch-02

Check in browser
$ localhost:88
