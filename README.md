 Features
- Reads games from a specified installation directory.
- Generates unique AppIDs for non-Steam games.
- Fetches grid, hero,headers,and logo images from SteamGridDB.
- Adds new games to Steam shortcuts.
- Removes shortcuts for games that are no longer installed.
- finds largest .exe in game folder and adds that as the game executable. You will need to check if the correct .exe has been chosen as I'm not sure how else to do this which isn't complex.
- logging


## Requirements
- Python 3.x
- 'requests' library
- 'vdf' library

- steam_user_data_path: Path to the Steam userdata config folder.
- game_installation_path: Path to the directory where your games are installed.
- steamgriddb_api_key: Your SteamGridDB API key.
- steamdir_path: Path to your Steam directory.


## Usage
- Change the directories in the script.
- Install required libraries.
```py
pip install requests vdf

