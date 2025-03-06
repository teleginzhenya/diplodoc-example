[API](../../overview.md) / [Configuration](../overview.md) / ChartLegend

Defined in: [src/types/chart/legend.ts:3](https://github.com/gravity-ui/charts/blob/6aea3bcf86facdd4a019a7e612d7ac7e27006c35/src/types/chart/legend.ts#L3)

## Properties

| Property | Type | Description |
| ------ | ------ | ------ |
| <a id="align"></a> `align?` | `"center"` \| `"left"` \| `"right"` | The horizontal alignment of the legend box within the chart area. **Default** `center` |
| <a id="colorscale"></a> `colorScale?` | `object` | - |
| `colorScale.colors` | `string`[] | - |
| `colorScale.domain?` | `number`[] | - |
| `colorScale.stops?` | `number`[] | - |
| <a id="enabled"></a> `enabled?` | `boolean` | - |
| <a id="itemdistance"></a> `itemDistance?` | `number` | Defines the pixel distance between each legend item **Default** `20` |
| <a id="itemstyle"></a> `itemStyle?` | [`BaseTextStyle`](../../Series/General/interfaces/BaseTextStyle.md) | CSS styles for each legend item |
| <a id="margin"></a> `margin?` | `number` | The space between the legend and the axis labels or chart area. **Default** `15` |
| <a id="title"></a> `title?` | `object` | - |
| `title.align?` | `"center"` \| `"left"` \| `"right"` | The horizontal alignment of the title. |
| `title.margin?` | `number` | The distance(in pixels) between the main content of the legend and its title Defaults to 4 for horizontal axes, 8 for vertical. |
| `title.style?` | `Partial`\<[`BaseTextStyle`](../../Series/General/interfaces/BaseTextStyle.md)\> | CSS styles for the title |
| `title.text?` | `string` | - |
| <a id="type"></a> `type?` | `"discrete"` \| `"continuous"` | Different types for different color schemes. If the color scheme is continuous, a gradient legend will be drawn. Otherwise, samples for different point values **Default** `'discrete'` |
| <a id="width"></a> `width?` | `number` | - |
