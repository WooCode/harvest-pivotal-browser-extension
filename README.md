#  PivotalTracker -> Harvest Chrome Extension

A Chrome browser extension bridging the gap between Pivotal Tracker and Harvest.

> Google Chrome is the only supported browser.

# Installation

## Manually

- Clone the repository and `cd` into it
- Run `npm install` to get the dependencies
- Install gulp globaly `npm install --global gulp`
- Run `gulp`
- If successful you should now see `/dist` folder in the repository root
- Go to Chrome -> click the three dots in the upper right corner
  - Choose `More tools -> Extensions`
  - Click the button `Load unpacked` and select the `/dist`
- Done! Now navigate to Pivotal Tracker

## Automatically

Chrome Webstore coming soon


## Original project

This project is a fork from a previous [project](https://github.com/codeandcraftinc/harvest-tracker-browser-extension) that have been discontinued. 

You can find the original extension in the [Chrome Webstore](https://chrome.google.com/webstore).



## Development

- clone this repository and `cd` into it
- run `npm install` to get the dependencies
- run `gulp` to build the extension
- in your Chrome extensions tab, enable "developer mode", then click the
  "load unpacked extension..." button and select the `dist/` directory within
  the location where you cloned this repository
- navigate to a PivotalTracker project in your browser and voilá!
