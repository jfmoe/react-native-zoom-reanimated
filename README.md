# react-native-zoom-reanimated

Zoom component on React Native + react-native-reanimated + react-native-gesture-handler

* You can zoom any View, Image or whatever.
* Can be used in FlatList (see Preview below).

## Preview

https://user-images.githubusercontent.com/11584712/174407015-2cd13692-a32e-4591-8cce-b47f6edb3cb9.mp4

## Getting started

Install the library using either Yarn:

```
yarn add kesha-antonov/react-native-zoom-reanimated
```

or npm:

```
npm install --save kesha-antonov/react-native-zoom-reanimated
```




## Usage

```javascript
import Zoom from 'kesha-antonov/react-native-zoom-reanimated'
```

## Example

```jsx
import Zoom from 'kesha-antonov/react-native-zoom-reanimated'


...
  <Zoom>
    <Image ... />
  </Zoom>

...
```

# Reference

#### Parameters

| Name    | Type   | Required | Description                               |
| ------- | ------ | -------- | ----------------------------------------- |
| style  | ViewPropTypes.style | No      | Container style |
| contentContainerStyle  | ViewPropTypes.style | No      | Content container style |


## License

The library is released under the MIT licence. For more information see [`LICENSE`](/LICENSE).