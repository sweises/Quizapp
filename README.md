# README


sudo apt update
sudo apt install postgresql postgresql-contrib libpq-dev
sudo systemctl start postgresql


sudo -u postgres createuser --superuser <euer wsl username>

export DB_USERNAME=<euer wsl username>
export DB_PASSWORD=<beliebiges passwort>

rails db:create
