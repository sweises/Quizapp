# README


sudo apt update
sudo apt install postgresql postgresql-contrib libpq-dev
sudo systemctl start postgresql



export DB_USERNAME=<euer wsl username>
export DB_PASSWORD=<beliebiges passwort>

sudo -u postgres createuser <euer wsl username> --superuser --pwprompt

rails db:create

rails server
