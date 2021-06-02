# PostgreSQL

## How to . . .
- Установка postrgesql

sh -c 'echo "deb http://apt.postgresql.org/pub/repos/apt $(lsb_release -cs)-pgdg main" > /etc/apt/sources.list.d/pgdg.list'
sh -c 
    sh - в ubuntu обычно  это симлинк к /bin/bash
        -с команда
wget --quiet -O - https://www.postgresql.org/media/keys/ACCC4CF8.asc | sudo apt-key add -

apt update

apt -y install postgresql-10

