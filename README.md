# Event Blocker

A UserScript to enhance privacy by blocking various browser events and modifying certain APIs.

## Description

This script aims to improve user privacy by intercepting and blocking common browser events that websites might use for tracking or fingerprinting. It also modifies certain APIs to introduce randomness and reduce the accuracy of timing-based fingerprinting techniques.

## Features

- Blocks various DOM events including visibility changes, mouse events, focus events, and more
- Modifies `requestAnimationFrame` to introduce random delays
- Alters the `Performance.now()` API to add random offsets
- Intercepts the Intersection Observer API to always report elements as not intersecting

## Usage

This script can be used with UserScript managers like Tampermonkey. It runs on all websites and starts execution at `document-start` to ensure maximum effectiveness.

## Testing

You can test the effectiveness of this script on https://webbrowsertools.com/test-always-active/

## Disclaimer

This script may break functionality on some websites. Use with caution and be prepared to disable it if you encounter issues with website functionality.

## Contributing

Feel free to submit issues or pull requests to improve the script's effectiveness or add new privacy-enhancing features.
