# react-native-meteor
react-native-meteor client, updated to be compatible with RN0.60.0+

[API Documentation](/docs/api.md)

# Installation
1. Install the package
2. Confirm you have peer dependencies installed (`@react-native-community/netinfo` and `@react-native-community/async-storage>=1.8.1`)

# Compatability
For React Native >=0.60.0 use this package

For React Native <0.60.0 use the original react-native-meteor package

**ATTENTION:** In order to shrink the repository, the following changes have been made from the original react-native-meteor library:
- cursoredFind is no longer an option. All .find() calls will return cursors (to match Meteor)
- `MeteorListView` & `MeteorComplexListView` have been removed
- `CollectionFS` has been removed
- `createContainer` has been removed
- Mixins (`connectMeteor`) have been removed
- `composeWithTracker` has been removed
