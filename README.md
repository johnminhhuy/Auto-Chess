# Auto-Chess
This is used to farm ELO on chess.com.
Only work on my machine (due to the position of the pixels)

# Resolutions
If you know how ts work, try to edit the position of the console panel in HTML (line 230: main.py)\
Also you need to take the image of the board's corners (Max size on chess.com, with DEV console opened)\
Top as black: tb.png\
Bottom as black: bob.png\
Top as white: tw.png\
Bottom as white: bw.png

# Nerfed and how to fixed
For chess.com to not detected this bot as a cheating account, here are some special settings that I used:\
- Set the Stockfish ELO to <opponent's ELO> + 300 (or 1300 if cannot detect the opponent ELO> (line 146: main.py)\
- Randomize the time to make the move in this range (0, currentTime / 10) (line 301: main.py)\
You can fix it if you like.

# How to use
Install python and stockfish\
Change the path to your own stockfish (line 139: main.py)\
Go into a game, wait 'till your the match start, run control.py (preferably with cmd) and quickly switch back to the chess game (with dev console currently open)\
If you encounter any problem, you can use the hotkey Ctrl + C to stop the program or ask ChatGPT to fix it =)

# Disclaimer
You should only use this for educational purpose.\
Only playing chess yourself will improve your skills!
