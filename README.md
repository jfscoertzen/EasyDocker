# EasyDocker
A list of docker cli commands to make it easier and prettier.

Clone to your home directory with:

`git clone https://github.com/jfscoertzen/EasyDocker ~/EasyDocker`

Add the following to any rc file of your choice (~/.bashrc or ~/.zshrc):

`source ~/EasyDocker/easy_docker_rc`

* Still work in progress

# Usage

The rc script will add the following commands:

`dockerps`

  get a list of running containers by project name

`dockerbash <container>`

  bash into a container. Similar to `docker exec -it <container> /bin/bash`
