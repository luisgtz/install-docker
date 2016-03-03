# install-docker
## Commands to install docker on ubuntu using curl

You can find the official documentation on [docker docs](https://docs.docker.com/v1.8/installation/ubuntulinux/)

Folow the next steps to install curl in case you does not have it install

    $ which curl
    $ sudo apt-get update
    $ sudo apt-get install curl


Follow the next steps to install latest docker version using curl

    $ curl -sSL https://get.docker.com/ | sh
    $ sudo usermod -aG docker $USER
    $ sudo service docker restart
    $ docker --version
    $ docker run hello-world
    $ docker run docker/whalesay cowsay 'Welcome to HPE'
  
