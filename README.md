# Expo Go: Blank/Unresponsive App with Custom Native Modules

This repository demonstrates a bug where a React Native app using a custom native module works correctly on a physical device or emulator, but displays a blank/unresponsive screen in Expo Go.  The issue arises from limitations in how Expo Go handles native modules.  The solution involves adapting the module setup or using a different approach for development and testing.

## Steps to Reproduce

1. Clone this repository.
2. Install dependencies using `npm install` or `yarn install`.
3. Attempt to run the app in Expo Go.
4. Observe the blank/unresponsive app. 
5. Run the app on a real device or emulator to verify that the native module is functioning correctly.

## Solution

The provided solution focuses on utilizing a different native module strategy that is compatible with Expo Go's limitations. This may include using Expo's built in modules or an alternative approach.