# ediop3C2
A c2 framework. Made it as .zip so every folder can be stored

for this to work edit the logins.txt which is located in src folder make it for example "random:password:2090-03-30"

+ u need to run pyhon3 main.py and then if u changed in the configuration.json to 127.0.0.1 port 5511 if yes js fo this run python3 main.py

+ then open a new tab terminal and use nc 127.0.0.1 5511

+ at user put the user for example mine is ediop3

+ at password put the password and then it's ready to go.



• Install Git and Python 3 on your server.

• Clone the ediop3C2 Github repository to your server via Git: $

• • git clone https://github.com/ediop3SquadALT/ediop3C2

• • Change the host address and C&C port in the configuration section in bot.py to your server address and C&C port.

• • Install the requirements.txt

• • Start the C2 server by executing the command:  • python main.py

• • Add accounts in logins.txt

•  using the format:

username:password:yyyy-mm-dd

• Configure the port • on the config.json

•  { "cnc_host": "0.0.0.0", "reg_host": "0.0.0.0", "cnc_port": 5511, "reg_port": 5512 }
