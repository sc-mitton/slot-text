# react-native-slot-text

To install dependencies:

```bash
bun install react-native-slot-text
```

This project was created using `bun init` in bun v1.1.21. [Bun](https://bun.sh) is a fast all-in-one JavaScript runtime.

https://github.com/user-attachments/assets/df5449f1-e20c-4a18-8687-67f29652d7b6


## Usage

```
    <Slider
        value={value}
        onValueChange={(value) => setValue(value[0])}
        minimumValue={0}
        maximumValue={limit_amount || 100}
        step={1}
        maximumTrackTintColor={theme.colors.quinaryText}
        minimumTrackTintColor={theme.colors.blueText}
        thumbTintColor={theme.colors.whiteText}
        thumbStyle={{
            width: 18,
            height: 18,
            shadowColor: theme.colors.navShadow,
            shadowOffset: { width: 0, height: 1 },
            shadowOpacity: 1,
            shadowRadius: 1,
        }}
    />
```

### Props

| Prop                | Type                  | Default  | Description                                                                                      |
|---------------------|-----------------------|----------|--------------------------------------------------------------------------------------------------|
| `value`             | '${number}'  | `N/A`    | The value to animate to. Can be a number or a string of numbers.                                  |
| `fontStyle`         | `Object`              | `N/A`    | The style of the text, passed as a `TextStyle` object.                                            |
| `animationDuration`  | `number`              | `200`    | The duration of the animation in milliseconds. Defaults to 200ms.                                 |
| `prefix`            | `string`              | `""`     | A prefix to the number, such as a currency symbol.                                                |
| `includeComma`      | `boolean`             | `false`  | Whether to include commas as thousand separators.                                                 |
