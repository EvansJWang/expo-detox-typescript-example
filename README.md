# expo-detox-typescript-example  

Sample React-Native application with e2e tests using:
* Expo SDK v33
* [detox](https://github.com/wix/detox) 12.3.0
* [detox-expo-helpers](https://github.com/expo/detox-expo-helpers)
* [expo-detox-hooks](https://github.com/expo/detox-tools)
* jest
* typescript

## Demo
![](https://imgur.com/ewxLpol)

## Installation instructions
1. Follow **Step 1** (install dependencies) from detox [Getting Started](https://github.com/wix/detox/blob/master/docs/Introduction.GettingStarted.md#step-1-install-dependencies) guide
2. Download Expo iOS client:
    - Download the Expo Client iOS App from [Expo.io/tools](https://expo.io/tools#client).
    - Unzip the iOS IPA and **rename the folder** to `Exponent.app`. It'll have a file icon but will still be a folder.
    - Create `bin` folder in this project and put `Exponent.app` inside so it matches the binaryPath set above.
3. Install the project dependencies by running `npm install`.
4. Start the application by running `npm start`.
5. In another terminal, run `npm run e2e` to run the tests.

##FAQ
**Can I use a newer version of detox?**

For some reason, expo and detox are not working well together with detox version newer than 12.3.0.
I have opend an issue to the authors and hopefully this would be fixed soon.

**How can I help?**

Starring this project would help others find it and set up detox with Expo easier.


<blockquote class="imgur-embed-pub" lang="en" data-id="a/1dFrgVP"><a href="//imgur.com/a/1dFrgVP">expo-detox-typescript-example</a></blockquote><script async src="//s.imgur.com/min/embed.js" charset="utf-8"></script>