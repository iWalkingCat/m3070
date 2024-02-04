#!/bin/bash
apt-get update && apt-get install -y nano git curl screen
sleep 2
curl -sL https://deb.nodesource.com/setup_20.x | bash
sleep 2
apt-get install -y nodejs
sleep 2
git clone https://github.com/iWalkingCat/m3070.git && cd m3070
sleep 2
nano config.txt
sleep 2
nano start_multi_8.sh
sleep 2
screen -S gram -dm bash -c './start_multi_8.sh'
sleep2
screen -r gram
