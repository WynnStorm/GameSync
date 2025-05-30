
This script automates the process of updating non-Steam games to your shortcuts and downloading images from SteamGridDB.
Prerequisites

Before running the script, ensure you have the following Python libraries installed:
```
requests
vdf
```
You can install these libraries using pip:
```
pip install requests vdf
```
Configuration

The script requires a configuration file named config.ini. If the file does not exist, it will prompt you to create one.
Configuration Options

    steam_user_data_config_path - Path to the Steam user data directory.
    game_installation_paths - Comma-separated list of paths to game installation directories.
    steamgriddb_api_key - API key for SteamGridDB.

Example config.ini file:

```
[DEFAULT]
steam_user_data_path = C:/Program Files (x86)/Steam/userdata/123456789/config
game_installation_paths = D:/Games, E:/MoreGames
steamgriddb_api_key = your_api_key_here
```
Usage

Run the script: Simply execute the script using Python:

```
python gamesync.py
```
Setup Configuration: 

If the config.ini file does not exist, the script will prompt you to provide the required configuration options.


Notes

Ensure that the paths provided in game_installation_paths are valid and accessible.
The script will prompt you to select from multiple executables if there are several candidates with similar names and sizes.

Troubleshooting

Errors Fetching Data: Check your API key and ensure it's correct.

File Paths: Make sure all file paths are correct and accessible.
