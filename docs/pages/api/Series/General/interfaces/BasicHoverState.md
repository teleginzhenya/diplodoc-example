[API](../../../overview.md) / [Series/General](../overview.md) / BasicHoverState

Defined in: [src/types/chart/series.ts:41](https://github.com/gravity-ui/charts/blob/6aea3bcf86facdd4a019a7e612d7ac7e27006c35/src/types/chart/series.ts#L41)

## Properties

| Property | Type | Description |
| ------ | ------ | ------ |
| <a id="brightness"></a> `brightness?` | `number` | How much to brighten/darken the point on hover. Use positive to brighten, negative to darken. The behavior of this property is dependent on the implementing color space ([more details](https://d3js.org/d3-color#color_brighter)). For example in case of using rgb color you can use floating point number from `-5.0` to `5.0`. Rgb color space is used by default. **Default** `0.3` |
| <a id="enabled"></a> `enabled?` | `boolean` | Enable separate styles for the hovered series. **Default** `true` |
