# React-native-snap-carousel example

I'm testing out react-native-snap-carousel, and the existing
[example](https://github.com/archriss/react-native-snap-carousel/tree/master/example)
is currently pinned to an outdated version of react-native, and wouldn't build
for me. This is a working example, as of December 2019, working with React
Native 0.61.5.

To test:
```
git clone https://github.com/kylebarron/react-native-snap-carousel-example
cd react-native-snap-carousel-example
yarn install
# For ios
cd ios
pod install
cd ..
# Run in emulator
react-native run-ios
```