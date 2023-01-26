![py-cord](2.3.2)

# Discord.py/Py-Cord bot template
This is a no-frills template for a Discord.py bot.

- Dockerized for easy deployment.
- Cogs, for clean, seperated code. 
- Pass your token  as an argument, so it's never in the code. 



# Running the bot

### Running locally on your machine
1. Clone the repository to your machine with:
```git clone https://github.com/Xarlos89/Discord-Bot---Template```

2. Open the Command Prompt/terminal to the Main.py file and run your bot using
```python main.py YOUR_BOT_TOKEN```
Where YOUR_BOT_TOKEN is your bot token. 

### Running using Docker
1. Clone the repository to your server:
```git clone https://github.com/Xarlos89/Discord-Bot---Template```

2. Change directory into the dir where the Dockerfile is stored and build the image.
```cd /Discord-Bot---Template && docker build -t Discord-Bot---Template .```

3. Run a new container using the built image
```docker run -d Discord-Bot---Template YOUR_BOT_TOKEN```