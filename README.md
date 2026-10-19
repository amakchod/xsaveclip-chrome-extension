# XSaveClip Chrome Extension

A lightweight Chrome extension that lets you open an X (Twitter) post in [XSaveClip](https://xsaveclip.com) with one click.

## Features

- Open supported X/Twitter posts directly in XSaveClip.
- Automatically pass the current post URL to the result page.
- Simple Manifest V3 extension.
- Uses the `activeTab` permission.
- No account required to use the extension.

## How It Works

1. Open a post on X (Twitter).
2. Click the XSaveClip extension icon.
3. The extension opens XSaveClip with the post URL.
4. Continue on [XSaveClip.com](https://xsaveclip.com).

## Installation

1. Download or clone this repository.
2. Open `chrome://extensions` in Chrome.
3. Enable **Developer mode**.
4. Click **Load unpacked**.
5. Select the extension folder containing `manifest.json`.

## Privacy

The extension is designed to pass the active post URL to XSaveClip when the user clicks the extension. It does not need access to all browsing history.

Review the source code in this repository to understand its behavior before installing it.

## Website

https://xsaveclip.com

## Disclaimer

This is an independent browser extension and is not affiliated with or endorsed by X/Twitter.
