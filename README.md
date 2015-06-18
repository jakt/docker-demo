## Install Docker
1. Install Docker: https://github.com/boot2docker/osx-installer/releases/latest
2. Run `boot2docker init && boot2docker start && eval "$(boot2docker shellinit)"`
3. Run `echo $(boot2docker ip) docker | sudo tee -a /etc/hosts > /dev/null`

## Try it out
1. Run `docker run --rm hello-world`
2. Run `docker run -it --rm ubuntu bash`

## Install Docker Compose
Run `curl -L https://github.com/docker/compose/releases/download/1.2.0/docker-compose-`uname -s`-`uname -m` > /usr/local/bin/docker-compose` and `chmod +x /usr/local/bin/docker-compose`

## Run the stack
1. Run `git clone https://github.com/jakt/docker-demo.git`
2. Run `docker-compose up`