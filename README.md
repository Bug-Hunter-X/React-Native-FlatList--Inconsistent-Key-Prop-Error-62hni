# React Native FlatList: Inconsistent Key Prop Error

This repository demonstrates a common error encountered when using the `FlatList` component in React Native: inconsistent or invalid `key` props.

The `key` prop is crucial for `FlatList`'s performance and correct rendering.  Using indices as keys, or keys that change unpredictably, often leads to rendering issues or crashes.

## Bug
The `FlatListBug.js` file shows an example of incorrect usage, using the index as the `key` prop. This leads to problems when items are added or removed from the data array.

## Solution
The `FlatListBugSolution.js` file presents a corrected implementation. It uses unique and consistent keys, ensuring the `FlatList` renders correctly and efficiently.

## How to reproduce the bug
1. Clone this repository.
2. Navigate to the project directory.
3. Run `npx react-native run-android` (or the equivalent for iOS).
4. Observe the incorrect rendering behavior in `FlatListBug.js`.
5. Then observe the corrected rendering in `FlatListBugSolution.js`
