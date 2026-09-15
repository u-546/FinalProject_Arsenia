# Arsenia

A tiny visual novel-style demo built in Python and pygame, inspired by RenPy-style dating sims: dialogue trees, branching choices, character sprites, and an affection meter that determines the ending to the story.

*What it is:*
- MC visits the lab, meets Arsenia, and the story branches from there based on what you say.
- All story content lives in dialogue.json, completely separate from the game code in main. Very renpy inspired. You dont have to touch the main to add new dialogues.
- Choices affect an affection meter, which determines one of three different endings.
- Full "Back" button lets you rewind through the entire conversation, affection changes included, not just the last line.
- 10 character expressions swapped dynamically based on the dialogue tone.

*What it's not:*
- Not a full game..this is a short demo/prototype, more of a proof of concept for imitating renpy with basic python.
- No save/load between sessions. Technical difficulties and lenght of the game didn't make sense for it to exist.

Built as a demo to explore how far a lightweight pygame engine can get toward that classic visual novel feel, without needing a full engine like RenPy.

AI use:
I have utilized AI mainly for the "back" function. Previously was supposed to be save/load function.
Otherwise AI was also used for polishing / bug hunting 

Main code inspiration has always been analyzing Ren.py itself.






edit: project moved from tb1 repo to it's own repo. Originally uploaded 2 days ago..
