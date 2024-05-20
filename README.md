## Overview

Overview
This project consists of various Chrome extensions developed to enhance the web browsing experience by adding useful functionalities. The extensions range from ad-blockers to media controllers and social media integration tools.

##
## Features

Features
- **GoodByeFaceBookAd**: Removes ads from Facebook pages.
- **JMU**: Controls media playback on Sony Entertainment Network's music site.
  - `back/`: Navigates back in the playlist.
  - `playOrStop/`: Plays or stops media playback.
  - `forward/`: Navigates forward in the playlist.
  - `twt/`: Integrates with Twitter to share media.
- **Jumblr**: Helps create Tumblr posts quickly.
- **JWeather**: Sets a weather icon based on Tokyo's weather forecast.

##
## Installation Instructions

Installation Instructions
1. **Clone the Repository**
    ```bash
    git clone https://github.com/jojonki/ChromeExtensions.git
    cd ChromeExtensions
    ```

2. **Load Extension in Chrome**
    - Open Chrome and navigate to `chrome://extensions/`.
    - Enable "Developer mode" by toggling the switch on the top right.
    - Click on the "Load unpacked" button and select the individual extension directory you want to load (e.g., `GoodByeFaceBookAd`, `JMU`, `Jumblr`, or `JWeather`).

3. **Dependencies**
    - Ensure you have a modern browser that supports extensions.
    - No additional dependencies are required as all the needed files (e.g., jQuery) are included in the repository.

##
## Usage Examples

Usage Examples

### GoodByeFaceBookAd

Once loaded, the extension will automatically run and remove side and main ads on Facebook.

### JMU

- **Back**
  - Go to `extensions/JMU/back/`, load it in Chrome. This will add the option to navigate back in the playlist on Sony Entertainment Network.
  
- **Play or Stop**
  - Go to `extensions/JMU/playOrStop/`, load it in Chrome. This will add the option to play or stop media playback on Sony Entertainment Network.
  
- **Forward**
  - Go to `extensions/JMU/forward/`, load it in Chrome. This will add the option to navigate forward in the playlist on Sony Entertainment Network.
  
- **Twitter Integration**
  - Go to `extensions/JMU/twt/`, load it in Chrome. This will provide options to tweet the current media information.

### Jumblr

- Go to `extensions/Jumblr/`, load it in Chrome.
- Use the extension to quickly create posts on Tumblr by selecting content and using the provided UI to share it.

### JWeather

- Go to `extensions/JWeather/`, load it in Chrome.
- The extension will display a weather icon based on the weather forecast for Tokyo, Japan.

##
## Code Summary

Code Summary

- `GoodByeFaceBookAd/js/main.js`
  - Contains logic to remove Facebook ads when the window loads.

- `JMU/back/js/popup.js`, `JMU/forward/js/popup.js`, `JMU/playOrStop/js/popup.js`
  - Controls the media playback functionality for Sony Entertainment Network.

- `JMU/twt/js/popup.js`
  - Integrates with Twitter to share content.

- `Jumblr/js/chrome_ex_oauth.js`, `Jumblr/js/chrome_ex_oauthsimple.js`
  - OAuth logic for Tumblr integration.

- `Jumblr/js/jumblr.js`
  - Logic to create Tumblr posts.

- `Jweather/js/back.js`
  - Fetches and displays weather data as an icon.

##
## License

License

This project is licensed under the BSD-3-Clause License. See the LICENSE file for more details.
```