## Features
 both  filesystem backups.
 it can be set daily backup time 
 its free pterodacyl Servers backup 

 apt update 
 apt install python3
`sudo apt install python3-pip

requests
2. python-dotenv
pip install requests && pip install python-dotenv
1. git clone https://github.com/ErroR404-sources/Pterodacyl-Automatically-Backup-whole-Servers-stored-.git
2. cd automated-backups
4. mv .env.example .env
5. Generate a client API key on your pterodactyl panel: `Account Settings > API Credentials > Create`
6. Replace the .env placeholder values with your own configuration.
python3 backup.py

`*** Please note: Ensure the account you used to generate the panel api key does not own any of the 

crontab -e
2. Add the following line: 0 4 * * * /path/to/env/bin/python3 /path/to/your/script/ErrorDevlopmentbackup.py

