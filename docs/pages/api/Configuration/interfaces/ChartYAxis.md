[API](../../overview.md) / [Configuration](../overview.md) / ChartYAxis

Defined in: [src/types/chart/axis.ts:107](https://github.com/gravity-ui/charts/blob/6aea3bcf86facdd4a019a7e612d7ac7e27006c35/src/types/chart/axis.ts#L107)

## Extends

- [`ChartAxis`](ChartAxis.md)

## Properties

| Property | Type | Description |
| ------ | ------ | ------ |
| <a id="categories"></a> `categories?` | `string`[] | - |
| <a id="grid"></a> `grid?` | `object` | The grid lines settings. |
| `grid.enabled?` | `boolean` | Enable or disable the grid lines. Defaults to true. |
| <a id="labels"></a> `labels?` | [`ChartAxisLabels`](ChartAxisLabels.md) | The axis labels show the number or category for each tick. |
| <a id="linecolor"></a> `lineColor?` | `string` | The color of the line marking the axis itself. |
| <a id="maxpadding"></a> `maxPadding?` | `number` | Padding of the max value relative to the length of the axis. A padding of 0.05 will make a 100px axis 5px longer. Defaults to 0.05 for Y axis and to 0.01 for X axis. |
| <a id="min"></a> `min?` | `number` | The minimum value of the axis. If undefined the min value is automatically calculate. |
| <a id="plotindex"></a> `plotIndex?` | `number` | Property for splitting charts. Determines which area the axis is located in. |
| <a id="plotlines"></a> `plotLines?` | [`AxisPlotLine`](AxisPlotLine.md)[] | An array of lines stretching across the plot area, marking a specific value |
| <a id="position"></a> `position?` | `"left"` \| `"right"` | Axis location. Possible values - 'left' and 'right'. |
| <a id="ticks"></a> `ticks?` | `object` | - |
| `ticks.pixelInterval?` | `number` | Pixel interval of the tick marks. Not applicable to categorized axis. The specified value is only a hint; the interval between ticks can be greater or less depending on the data. |
| <a id="timestamps"></a> `timestamps?` | `number`[] | - |
| <a id="title"></a> `title?` | `object` | - |
| `title.align?` | [`ChartAxisTitleAlignment`](../type-aliases/ChartAxisTitleAlignment.md) | Alignment of the title. |
| `title.margin?` | `number` | The pixel distance between the axis labels or line and the title. Defaults to 4 for horizontal axes, 8 for vertical. |
| `title.maxRowCount?` | `number` | Allows limiting of the contents of a title block to the specified number of lines. Defaults to 1. |
| `title.style?` | `Partial`\<[`BaseTextStyle`](../../Series/General/interfaces/BaseTextStyle.md)\> | CSS styles for the title |
| `title.text?` | `string` | - |
| <a id="type"></a> `type?` | [`ChartAxisType`](../type-aliases/ChartAxisType.md) | - |
