
1. install nodejs for npm and node commands
curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash -
sudo apt-get install nodejs


2. isntall watchman
git clone https://github.com/facebook/watchman.git
cd watchman
git checkout v4.9.0  # the latest stable release
./autogen.sh
./configure
make
sudo make install


apt-get install pkg-config


3. install nuclide server
npm install -g nuclide
sudo npm install -g nuclide@0.271.0



