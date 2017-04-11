# vagrant-java

My Vagrant template for a quick and easy webserver running Java and Apache Maven
The setup forwards 8081 to 80 and 443 to 8444. This can be modified in the BootStrap file. The "weird" ports are chosed because this machine was originally created to run [openEHR's adl-designer](http://github.cm/openehr/adl-designer).
 
## Installation

### Windows 10 (Administrative cmd.exe)

Please be aware that the setup can take some time.

```
cd <folder where to download vagrant machine>
choco install -y vagrant virtualbox git
git clone https://github.com/bpjohannessen/vagrant-java.git
vagrant up
vagrant ssh
```

### Linux (Ubuntu 16.04)

```
cd <folder where to install vagrant machine>
sudo apt-get install -y virtualbox vagrant git
git clone https://github.com/bpjohannessen/vagrant-java.git
vagrant up
vagrant ssh
```

## Currently tested setup:

**Windows 10**

* Vagrant 1.9.3
* VirtualBox 5.1.18

**Ubuntu 16.04**

* Vagrant 1.9.3
* VirtualBox 5.1.18