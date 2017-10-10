This repo aims to demonstrate an automated CentOS 7 image template build with Packer.

### Requirements
- Virtualbox
- Vagrant
- Packer

### How to run the demo?

1. Clone the repo 

`git clone https://github.com/benfab/demo-packer-centos7.git` 

`cd demo-packer-centos7`

2. Run Packer

`packer build centos7.json`

3. Add the box to Vagrant 

`vagrant box add  packer-centos7 packer-centos7.box`

4. Deploy the Vagrant environment 

`vagrant up`

5. Test the newly deployed machine 

`vagrant ssh` 
