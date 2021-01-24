# Mimic Engine
# How to Use
First Download both the Mimic-Engine folder and the renpy SDK folder from the repo. You will need to use renpy 3.5 for this project. 

Launch the renpy executable, either for Mac or Windows and select the Mimic Engine project. 

Now you all you need to do is just hit "Launch Project" in renpy.


# Inspiration
I had been a chess enthusiast for a while now and one of the most frustrating parts of chess for me has been to understand how the ELO system works and what my ELO score is. Most chess websites require you to manually adjust the AI's difficulty yourself but as a new player or a beginner you have no idea what your ELO is. As a beginner this can be overwhelming and confusing and so I built this project in order to create a more smooth and user-friendly experience. This can also help you get progressively better as you play the game because there are times that the AI might be too difficult or too easy when manually adjusting the difficulty.

# What it does
2 game modes: Player vs Player and Player vs Computer 
Highlights chess pieces when you hover over them. 
Highlights legal moves that can be made with a selected chess piece. 
Prevents illegal moves. 
Recent moves are shown on the left hand side of the game. 
You can flip sides mid-game. 
Tells you who's turn it is AI difficulty can start out from: Easy, Medium, or Hard. 
AI difficulty adjusts as you play the game in any difficulty.

# How I built it
Libraries used: 
Renpy for the visual engine 
python-chess for the game engine 
stockfish for the chess AI. 

Programming Language: 
Python. 

# Challenges
Unfortunately, I wasn't able to use traditional machine learning tools due to being short on time in this hackathon to train my model. However, I hope to use the traditional training and testing methods of machine learning for this alpha version of my chess engine.

# Accomplishments
I'm glad I got at least the game engine and visuals working. I can tweak them further to look better and optimize the speed of the game, but my main concern will be to develop my chess AI through more traditional machine learning models.

# What's next for Mimic Engine

I hope to use the traditional training and testing methods of machine learning after having built the alpha version of my chess engine. I hope to make the visuals a lot cleaner and iron out some bugs that may be present.
