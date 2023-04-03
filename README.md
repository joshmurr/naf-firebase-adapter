# Accelerate Editor Networked-AFrame Firebase Adapter

This is a fork of [networked-aframe/naf-firebase-adapter](https://github.com/networked-aframe/naf-firebase-adapter) for use with the [Accelerate Editor](https://accelerate-editor.web.app/).

## Change Log

- The only minor change is to look for the Firebase config in `window.top` (the parent window in the Accelerate Editor), [line 26 of index.js](https://github.com/joshmurr/naf-firebase-adapter/blob/master/src/index.js#L26).
