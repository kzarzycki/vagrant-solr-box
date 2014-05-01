# Vagrant Solr box

Box to get a Solr environment quickly up and running in a VM. If you plan to modify the Solr configuration copy the content of this repo to a new repo.

## Cloning the repo

This repo uses submodules, so please add --recursive to git clone call.

 git clone https://github.com/kzarzycki/vagrant-solr-box.git --recursive
 
## Running the box

1. Install [Vagrant](http://www.vagrantup.com/)
2. `vagrant up`
3. Open http://localhost:8983/solr/#/ (on host)
