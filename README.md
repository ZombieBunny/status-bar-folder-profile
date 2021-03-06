# Display the current root directory name in the status bar.

This extension was birthed out of the need to be more productive, while being faced with a very niche use case for needing to know the current directory name while having the editor opened in full screen mode with the explorer minimized, on MacOS. The directory name will display automatically if the directory includes a 'package.json' file, but can be triggered with the following command:

* Press `Shift+CMD+p` (macOS) to open command pallet and enter `Display directory on status bar`

## Features

The extension extracts the current directory path and capitalizes the first letter of each word thats been seperated by a `-` (dash) and displays this at the first position on the left of the status bar.

## Release Notes

Just displays the current root directory name at the first position on the left of the status bar. The directory name will display if the directory includes a package.json file.

### 1.0.0

Initial release.


If you want to improve this document or have a feature you want to add, please submit a PR to the [git repo](https://github.com/ZombieBunny/status-bar-folder-profile).
