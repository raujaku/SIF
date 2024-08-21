# Steam Image Fetcher (SIF)

Steam Image Fetcher is a Python script that automates the process of adding non-Steam games to your Steam library and fetching appropriate images for them from SteamGridDB.

## Features

- Automatically detects installed games in specified directories
- Adds non-Steam games to your Steam library
- Fetches game images (posters, banners, heroes, logos, and icons) from SteamGridDB
- Supports animated images
- Caches SteamGridDB searches to reduce API calls
- Provides a progress bar for better user feedback

## Requirements

- Python 3.6+
- Steam account
- SteamGridDB API key

## Installation


1. Install the required packages:
   ```
   PyYAML
   tqdm
   vdf
   requests
   ```

## Configuration

On first run, the script will prompt you to enter the following information:

- Steam user data path
- Game installation paths (comma-separated)
- SteamGridDB API key
- Whether to search for animated images

This information will be saved in a `config.yaml` file for future use.

## Usage

Run the script
   ```
   python SIF.py
   ```
The script will:
1. Detect installed games
2. Add them to your Steam library
3. Fetch appropriate images from SteamGridDB
4. Update your Steam shortcuts file

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [SteamGridDB](https://www.steamgriddb.com/) for providing the game images
- [tqdm](https://github.com/tqdm/tqdm) for the progress bar functionality
- [PyYAML](https://pyyaml.org/) for YAML file handling
- [vdf](https://github.com/ValvePython/vdf) for Valve's KeyValues format handling
- [Maikeru86](https://github.com/Maikeru86/GameSync) for the base code
## Disclaimer

This tool is not affiliated with Valve Corporation or Steam. Use at your own risk.
