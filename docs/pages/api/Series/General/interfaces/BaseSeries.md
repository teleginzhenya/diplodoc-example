[API](../../../overview.md) / [Series/General](../overview.md) / BaseSeries

Defined in: [src/types/chart/base.ts:3](https://github.com/gravity-ui/charts/blob/6aea3bcf86facdd4a019a7e612d7ac7e27006c35/src/types/chart/base.ts#L3)

## Extended by

- [`AreaSeries`](../../Area/interfaces/AreaSeries.md)
- [`BarXSeries`](../../Bar-X/interfaces/BarXSeries.md)
- [`BarYSeries`](../../Bar-Y/interfaces/BarYSeries.md)
- [`LineSeries`](../../Line/interfaces/LineSeries.md)
- [`PieSeries`](../../Pie/interfaces/PieSeries.md)
- [`ScatterSeries`](../../Scatter/interfaces/ScatterSeries.md)
- [`TreemapSeries`](../../Treemap/interfaces/TreemapSeries.md)
- [`WaterfallSeries`](../../Waterfall/interfaces/WaterfallSeries.md)

## Properties

| Property | Type | Description |
| ------ | ------ | ------ |
| <a id="cursor"></a> `cursor?` | `string` | You can set the cursor to "pointer" if you have click events attached to the series, to signal to the user that the points and lines can be clicked. |
| <a id="datalabels"></a> `dataLabels?` | `object` | Options for the series data labels, appearing next to each data point. |
| `dataLabels.allowOverlap?` | `boolean` | **Default** `false` |
| `dataLabels.enabled?` | `boolean` | Enable or disable the data labels **Default** `true` |
| `dataLabels.html?` | `boolean` | Allows to use any html-tags to display the content. The element will be displayed outside the box of the SVG element. **Default** `false` |
| `dataLabels.padding?` | `number` | **Default** `5` |
| `dataLabels.style?` | `Partial`\<[`BaseTextStyle`](BaseTextStyle.md)\> | - |
| <a id="visible"></a> `visible?` | `boolean` | Initial visibility of the series |
