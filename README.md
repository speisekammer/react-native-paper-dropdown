react-native-paper-dropdown
===========================

**Fork of
[react-native-paper-dropdown](https://fateh999.github.io/react-native-paper-dropdown/#/README)**


Install
-------

```
npm install @hashiprobr/react-native-paper-dropdown
```


Removed props
-------------

| name         | description              |
|--------------|--------------------------|
| visible      | not available            |
| onDismiss    | not available            |
| showDropDown | not available            |
| setValue     | renamed to onChangeValue |


Added props
-----------

| name                 | description                                                                                                                                 |
|----------------------|---------------------------------------------------------------------------------------------------------------------------------------------|
| onChangeValue        | renamed from setValue                                                                                                                       |
| disabled             | analogous to the [TextInput disabled prop](https://callstack.github.io/react-native-paper/text-input.html#disabled)                         |
| editable             | analogous to the [TextInput editable prop](https://callstack.github.io/react-native-paper/text-input.html#editable)                         |
| style                | analogous to the [TextInput style prop](https://callstack.github.io/react-native-paper/text-input.html#style)                               |
| touchableProps       | analogous to the [TouchableRipple props](https://callstack.github.io/react-native-paper/touchable-ripple.html)                              |
| touchableStyle       | analogous to the [TouchableRipple style prop](https://callstack.github.io/react-native-paper/touchable-ripple.html#style)                   |
| error                | analogous to the [TextInput error prop](https://callstack.github.io/react-native-paper/text-input.html#error)                               |
| selectionColor       | analogous to the [TextInput selectionColor prop](https://callstack.github.io/react-native-paper/text-input.html#selectionColor)             |
| underlineColor       | analogous to the [TextInput underlineColor prop](https://callstack.github.io/react-native-paper/text-input.html#underlineColor)             |
| activeUnderlineColor | analogous to the [TextInput activeUnderlineColor prop](https://callstack.github.io/react-native-paper/text-input.html#activeUnderlineColor) |
| outlineColor         | analogous to the [TextInput outlineColor prop](https://callstack.github.io/react-native-paper/text-input.html#outlineColor)                 |
| activeOutlineColor   | analogous to the [TextInput activeOutlineColor prop](https://callstack.github.io/react-native-paper/text-input.html#activeOutlineColor)     |
| dense                | analogous to the [TextInput dense prop](https://callstack.github.io/react-native-paper/text-input.html#dense)                               |
| iconStyle            | analogous to the [TextInput.Icon style prop](https://callstack.github.io/react-native-paper/text-input-icon.html#style)                     |
