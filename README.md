
███████╗ ██████╗ ███████╗███████╗███████╗     ████████╗ ██╗  ██╗ ███████╗
██╔════╝██╔═══██╗██╔════╝██╔════╝██╔════╝    ╚══██╔══╝ ██║  ██║ ██╔════╝
█████╗  ██║   ██║█████╗  █████╗  ███████╗           ██║    ███████║ █████╗  
██╔══╝  ██║   ██║██╔══╝  ██╔══╝  ╚════██║           ██║    ██╔══██║ ██╔══╝  
██║     ╚██████╔╝███████╗███████╗███████║          ██║    ██║  ██║ ███████╗
╚═╝      ╚═════╝ ╚══════╝╚══════╝╚══════╝          ╚═╝    ╚═╝  ╚═╝ ╚══════╝

                ⚫ GUESS THE NUMBER ⚫
         A cheeky fullscreen number guessing game
------------------------------------------------------------------------

📄 How to Play:
---------------
- The game will choose a secret number between 0 and a configurable max (default is 100).
- Your job is to guess it!
- Enter your guesses using the keyboard and press "Submit Guess".
- The game will tell you if the number is higher or lower than your guess.
- Try to guess it in as few attempts as possible!
- The game keeps track of your BEST score (least attempts to win).

But... the game may also **mock** your bad guesses. Stay sharp 👀


🔧 Requirements:
---------------
✓ Python 3.10 or later (tested on 3.13)
✓ Runs on Windows (fullscreen, GUI)
✓ No external libraries required (built-in `tkinter`, `json`, etc.)

To check Python version:
→ Open Command Prompt and type:
    python --version

To install Python:
→ https://www.python.org/downloads/


🚀 How to Launch:
-----------------
1. Put all files in the same folder:
   • `guess_game.py` (the main game script)
   • `main.bat` (use this if admin is needed)
   • `config.json` *(optional – generated automatically if missing)*
   • `best_score.json` *(optional – generated automatically if missing)*

2. Double-click `main.bat`  
   OR open a terminal (admin) and type:
   ```bash
   python guess_game.py



🔁 How to Reset High Scores :
------------------------------------------------------------
The game saves your *best score* in a file called:

    best_score.json

To reset your high score:
1. Navigate to the game folder (where the `.py` file is).
2. Find and open `best_score.json` using Notepad or any text editor.
3. Replace everything inside with this:

    {
        "best_score": null
    }

4. Save and close the file.
Now your best score is cleared!



🎯 Changing the Maximum Number (Guessing Range):
------------------------------------------------
The game default range is **0 to 100**, but you can customize it.

To change this:
1. In the same game folder, open the file:

    config.json

2. You’ll see something like:

    {
        "max_guess": 100
    }

3. Change the number to anything you want. For example:

    {
        "max_guess": 500
    }

4. Save the file.

The next time you launch the game, it will use the new number range!

📝 Tip: The game will automatically regenerate these files if they’re missing or deleted —  
so don’t worry if you mess something up, you can just delete them and they’ll come back.




📌 Why I Included This Explanation:
-----------------------------------
These days, many people are cautious about running `.exe` files — and rightfully so.  
It's easy for malware to hide in a binary, and you can’t really “look inside” to know what’s going on.

I added this part to be **fully transparent** with you:

• I want you to know this script is safe and simple.
• I’m not hiding anything — that’s why I’m giving you the `.py` version.
• If you're skeptical or curious, you can open it in any text editor and read exactly what it does.

This way, you can:
→ **Verify** it's harmless  
→ **Learn** from the code if you're interested in Python  
→ **Trust** that there's no shady stuff behind the scenes

