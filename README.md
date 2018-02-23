As of 8.0.0 [Polidea/react-native-ble-plx](https://github.com/Polidea/react-native-ble-plx) isn't compatible with Expo 25.0.0 because of the `<React/Blah.h` imports. This is a minor fork that replaces them with `"Blah.h"`

I strongly suggest you don't use this as I can't guarantee I'll keep it up to date nor can I guarantee it'll even work.

You want the `patch_header_imports` branch so switch out for this in your package.json

`"react-native-ble-plx": "JofArnold/react-native-ble-plx-expo#patch_header_imports"`
