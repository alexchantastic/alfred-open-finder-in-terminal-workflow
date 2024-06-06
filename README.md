# alfred-open-finder-in-terminal-workflow

![Screenshot](https://github.com/alexchantastic/alfred-open-finder-in-terminal-workflow/assets/604167/b40951dc-9431-4bb4-92c4-487a4b57d3eb)

An [Alfred 5](https://www.alfredapp.com/) workflow opening the currently selected or focused Finder folder in Terminal.

## Configuration

There isn't any configuration necessary with the workflow itself. However, if you would like to use your terminal of choice, you can configure Alfred to specify a [custom terminal application](https://www.alfredapp.com/help/features/terminal/) to use.

If you are using iTerm2, check out [vitorgalvao/custom-alfred-iterm-scripts](https://github.com/vitorgalvao/custom-alfred-iterm-scripts) for how to configure Alfred.

## Installation

1. [Download the workflow](https://github.com/alexchantastic/alfred-open-finder-in-terminal-workflow/releases/latest)
2. Double click the `.alfredworkflow` file to install

Note that the [Alfred Powerpack](https://www.alfredapp.com/powerpack/) is required to use workflows.

## Usage

1. Use the keyword `ft` to trigger the workflow
2. Press `enter` to open the current or selected Finder folder in Terminal

If you don't have anything selected in Finder, the workflow will open the current Finder folder. If you have a folder selected in Finder, the workflow will open the selected folder. If you have a non-folder item selected in Finder, it will open the current Finder folder.

## License

Code released under the [MIT License](https://github.com/alexchantastic/alfred-open-finder-in-terminal-workflow/blob/main/LICENSE).
