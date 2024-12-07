# GitHub Release Notes Watcher

> This file was AI Generated

## Description

The GitHub Release Notes Watcher is a web application that allows users to monitor and view the latest release notes of specified GitHub repositories. The application fetches the latest release notes from GitHub repositories specified by the user and displays them in a user-friendly format. Users can manage the list of repositories they want to monitor through a settings interface. The application caches the fetched release notes to improve performance and reduce the need for repeated API calls. Users can manually check for updates, clear the cache, and view the last updated time.

## Key Features

- Monitor and view the latest release notes of specified GitHub repositories.
- Fetches the latest release notes from GitHub repositories specified by the user.
- Displays release notes in a user-friendly format.
- Manage the list of repositories to monitor through a settings interface.
- Caches fetched release notes to improve performance.
- Manually check for updates, clear the cache, and view the last updated time.
- Uses the `marked` library to parse Markdown and `DOMPurify` to sanitize the HTML output.
- Provides a fallback mechanism if the `marked` library fails to load.
- Includes a responsive design with a dark theme.
- Provides error handling and user feedback for failed repository updates.

## Instructions

1. Open the `index.html` file in a web browser.
2. Enter the GitHub repositories you want to monitor in the settings interface, one per line, in the format: `owner/repo`.
3. Click "Save" to save the list of repositories.
4. The application will fetch and display the latest release notes for the specified repositories.
5. Use the "Check for Updates" button to manually check for updates.
6. Use the "Clear Cache" button to clear the cached release notes.
7. The "Last updated" time will show the last time the release notes were fetched.


## Acknowledgments

- [marked](https://github.com/markedjs/marked) - A library for parsing Markdown.
- [DOMPurify](https://github.com/cure53/DOMPurify) - A library for sanitizing HTML output.
