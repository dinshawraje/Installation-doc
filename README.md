# Installation document for RVM, MONGO and NODE

## Installation of rvm:

  - sudo apt-get install git-core curl zlib1g-dev build-essential libssl-dev libreadline-dev libyaml-dev libsqlite3-dev sqlite3 libxml2-dev libxslt1-dev libcurl4-openssl-dev python-software-properties
  - sudo apt-get update
  - sudo apt-get install libgdbm-dev libncurses5-dev automake libtool bison libffi-dev
  - curl -L https://get.rvm.io | bash -s stable
  - source /home/dinshaw/.rvm/scripts/rvm
  - echo "source ~/.rvm/scripts/rvm" >> ~/.bashrc
  - rvm install 2.1.5
  - rvm list

##  Installation of Mongo:

 - sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv 7F0CEB10
 - Generate a file with the MongoDB repository url:
 - echo 'deb http://downloads-distro.mongodb.org/repo/ubuntu-upstart dist 10gen' | sudo tee /etc/apt/sources.list.d/mongodb.list
 - sudo apt-get update
 - sudo apt-get install mongodb-org
 - ps -ef | grep mongo (yippi mongo is running)
 - mongo 
  

## Installation of Node:

  - curl https://raw.githubusercontent.com/creationix/nvm/v0.10.0/install.sh | sh
  
  - $ source ~/.profile or $ source ~/.bash_profile
  
  - nvm install 0.10.28 # node version (0.10.28 or so on)
  
  - nvm install 0.10.28 # node version (0.10.28 or so on)
  
  -  nvm use 0.10.28
