# Discord-Python-Bot
This is a rewrite version of `https://github.com/jediknight813/llama-cpp-discord-bot` to use a local instance of `llama.cpp` with it's `api_like_OAI.py` for a private Discord AI bot.

Easy to install with Ubuntu server 22.04

Clone the repo with:
`git clone https://github.com/zooteld/Discord-Python-Bot.git`

Enter and install dependancies
`cd Discord-Python-Bot && pip install -r requirements.txt`

Make your .env file and edit it with nano
`cp -r .env.example .env && nano .env`

simple as:
	1) Paste your Discord bot token.
	2) Point the `API_URL` at your local instance of `api_like_OAI.py` instance.
	
To run:
	1) `cd scripts`
	2) `chmod +x run.sh`
	3) `./run.sh`
	
This assumes you know how to make a discord app in their developers portal. 
Im not covering that there are plenty of others that have.