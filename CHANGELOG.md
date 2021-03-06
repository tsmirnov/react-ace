# Changelog

## Next Minor Release - TBD

* Fully move to TypeScript interally
* Publish typings for the split editor
## 5.1.2

* Resize on component did mount and component did update. Fixes #207 and #212. 

## 5.1.1

* Fix TypeScript definitions for EditorProps

## 5.1.0

* Editor options do not get reverted due to default props #226
* Markers can be unset to an empty value #229
* Typescript update to set state to empty object instead of undefined


## 5.0.1

* Fixes file extension issue related to `5.0.0`.

## 5.0.0

* Support for a Split View Editor - see more about the Split View editor [here](https://github.com/securingsincity/react-ace/blob/master/docs/Split.md)
* Ace Editor will now warn on mispelled editor options
* All new documentation

## 4.4.0

* Ace's resize method will be called when the prop `width` changes

## 4.3.0

* Adds support for `onSelectionChange` event
* Add the `Event` as an optional argument to the `onChange` prop
* All new examples

## 4.2.2

* [bugfix] should not handle markers without any markers

## 4.2.1

* Use `prop-type` package instead of React.PropType

## 4.2.0

* Fix `ref` related error

## 4.1.6

* Reverse `PureComponent` use in AceEditor back to `Component`

## 4.1.5

* Add ability to set `scrollMargins`

## 4.1.4

* TypeScript Definitions
