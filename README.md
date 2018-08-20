# vagrant-docker

This project is an example of how to use Docker instead of Virtual Machines (eg VirtualBox)

For this example we have used the Ubuntu image for Vagrant Docker.

## Usage

Clone this repository on your local machine.

``` bash
git clone git@github.com:jeastman19/vagrant-docker.git
```

Then execute:

```bash
vagrant up
```
This will download the nishidayuya / docker-vagrant-ubuntu image if it does not already exist on your local machine, it will create the container and execute it.

Then we can enter with ssh to the container executing:

``` bash
vagrant ssh
```
