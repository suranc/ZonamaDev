# ZonamaDev

Zonama - The living planet, or in our world an easily deployed development environment for working on the server code of swgemu's Core3 (https://www.swgemu.com/)

## Quickstart

Download and install VirtualBox and Vagrant

```
git clone https://github.com/lordkator/ZonamaDev.git
cd ZonamaDev/host
vagrant plugin install vagrant-reload
vagrant plugin install vagrant-vbguest
vagrant up
```

Currently this takes about 10 mins on a fairly fast internet connection and nice sized box.
