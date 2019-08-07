# react-native-uuid-generator

A simple wrapper around the native iOS and Android UUID classes.
Exposes a single method, `getRandomUUID`.

Forked from: https://github.com/Traviskn/react-native-uuid-generator

## Getting started


`Requires react > 0.60 for auto linking`

Add to packages.json
`"react-native-uuid-generator": "github:cristianoccazinsp/react-native-uuid-generator"`


## Usage

This library supports both callback and promise interfaces.

```javascript
import UUIDGenerator from 'react-native-uuid-generator';

// Callback interface
UUIDGenerator.getRandomUUID((uuid) => {
  console.log(uuid);
});
// => "42A8A87A-F71C-446B-B81D-0CD16A709625"

// Promise interface
UUIDGenerator.getRandomUUID().then((uuid) => {
  console.log(uuid);
});
// => "BD6120BD-3612-4D56-8957-99F5D6F02C52"
```

