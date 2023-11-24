# LuckyPaste Alfred Workflow

An Alfred workflow that lets you search for links and images with Google Custom Search directly from your clipboard and paste the results instantly.

## Features

- **LuckyPaste**: Quickly fetches the first Google search result link for a given query.
- **LuckyPic**: Retrieves the first image result for a given query and saves it to a temporary directory.

## Prerequisites

Before you start using LuckyPaste, you need to have:

- Alfred 4 with a Powerpack license.
- Python 3 installed on your macOS.
- A Google Custom Search Engine (CSE) created and an API key obtained from the [Google Developer Console](https://console.developers.google.com/).

## Setup

1. Clone this repository or download the workflow file.
2. Add the workflow to Alfred.
3. Set the following environment variables in the workflow:
   - `API_KEY`: Your Google API key.
   - `CX`: The custom search engine ID for your Google CSE.

## Usage

### LuckyPaste

1. Select text anywhere on your Mac.
2. Use the assigned hotkey or Alfred keyword to trigger the workflow.
3. The workflow will search Google with the selected text and paste the first result's URL.

### LuckyPic

1. Select text anywhere on your Mac.
2. Use the assigned hotkey or Alfred keyword to trigger the workflow.
3. The workflow will search Google Images with the selected text.
4. The first image result will be downloaded to `~/AlfredTemp`.

## Customization

You can customize the workflow by changing the hotkeys, keywords, and modifying the scripts to adjust the behavior as per your needs.

## Contribution

Contributions are welcome. Please fork the repository and submit a pull request with your enhancements.

## License

Distributed under the MIT License. See `LICENSE` for more information.

The above README provides an overview of the Alfred workflow, its features, prerequisites, setup instructions, and usage details. It also mentions the ability to customize the workflow, how to contribute to its development, and the type of license it's distributed under. The actual Python scripts are referenced but not included in the README, assuming they will be viewable within the repository itself.
