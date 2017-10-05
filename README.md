# Collaborative Online Judge System
This is a full stack system supporting collaborative coding, editing, compiling and execution.
## Major Use Cases:
1. Multiple users can edit the same piece of code simultaneously.
2. A user can browse pre-stored coding problem list.
3. A user can get details of a specific coding problem by clicking the problem in the list.
4. User can submit the code through ‘submit’ button to submit the code to solve the chosen question. The result, including 
compiling, correctness and running time, will be displayed to user.


## Build Instruction
 1. Install NodeJs:

    sudo apt-get update

    curl -sL https://deb.nodesource.com/setup_7.x | sudo -E bash -

    sudo apt-get install -y nodejs

 2. Install Nodemon

    npm install -g nodemon

 4. Install angular/cli

    npm install -g @angular/cli

 5. Install Redis

    wget http://download.redis.io/releases/redis-3.2.6.tar.gz

    tar xzf redis-3.2.6.tar.gz

    cd redis-3.2.6

    make

    sudo make install

    cd utils

    sudo ./install_server.sh


 6. Install python 2.7 and pip

 7. Install Docker: 

    curl -fsSL https://get.docker.com/ | sh

 8. Setup docker permission: 

    sudo usermod -aG docker $(whoami)

   To start docker when the system boots: sudo systemctl enable docker
