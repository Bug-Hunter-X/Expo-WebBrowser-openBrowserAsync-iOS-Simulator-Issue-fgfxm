# Expo WebBrowser.openBrowserAsync iOS Simulator Issue

This repository demonstrates a bug where `WebBrowser.openBrowserAsync` from the Expo SDK does not work correctly in the iOS simulator.  The function appears to execute without error but does not actually open the specified URL in a browser.

## Bug Reproduction

1. Clone this repository.
2. Run `npm install` or `yarn install`.
3. Run the app in an iOS simulator.
4. Observe that tapping the button does not open the URL in a browser, despite the console log showing a successful result.

## Solution

The solution involves using a different approach to open external URLs in the iOS simulator.  See the `bugSolution.js` file for a working solution.