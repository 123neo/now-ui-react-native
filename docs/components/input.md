# Input

This components extends [Galio](https://galio.io?ref=now-uirn-docs)'s Input component.

### Usage

Simple Example:

```
<Block style={{ paddingHorizontal: theme.SIZES.BASE }}>
    <Input
      right
      placeholder="Icon Right"
      iconContent={
        <Icon
          size={11}
          color={nowTheme.COLORS.ICON}
          name="search-zoom-in"
          family="NowExtra"
        />
      }
    />
  </Block>
```

<p align="center">
  <img src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/now-ui-react-native/inputs.png" height="370px">
</p>

### Props

|    Prop    | Type | Default |                       Description                        |
| :--------: | :--: | :-----: | :------------------------------------------------------: |
| shadowless | bool |  false  |                removes shadow from input                 |
|  success   | bool |  false  |  visual identification of a successfully written input   |
|   error    | bool |  false  | visual identification of an unsuccessfully written input |

### Galio Inputs

For more props and buttons please check out the [galio buttons section](https://galio.io/docs/#/components/input).
