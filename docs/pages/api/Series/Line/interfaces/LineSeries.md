[API](../../../overview.md) / [Series/Line](../overview.md) / LineSeries

Defined in: [src/types/chart/line.ts:34](https://github.com/gravity-ui/charts/blob/6aea3bcf86facdd4a019a7e612d7ac7e27006c35/src/types/chart/line.ts#L34)

## Extends

- [`BaseSeries`](../../General/interfaces/BaseSeries.md)

## Type Parameters

| Type Parameter | Default type |
| ------ | ------ |
| `T` | [`MeaningfulAny`](../../../Utilities/type-aliases/MeaningfulAny.md) |

## Properties

| Property | Type | Description |
| ------ | ------ | ------ |
| <a id="color"></a> `color?` | `string` | The main color of the series (hex, rgba) |
| <a id="cursor"></a> `cursor?` | `string` | You can set the cursor to "pointer" if you have click events attached to the series, to signal to the user that the points and lines can be clicked. |
| <a id="dashstyle"></a> `dashStyle?` | `"Dash"` \| `"DashDot"` \| `"Dot"` \| `"LongDash"` \| `"LongDashDot"` \| `"LongDashDotDot"` \| `"ShortDash"` \| `"ShortDashDot"` \| `"ShortDashDotDot"` \| `"ShortDot"` \| `"Solid"` | Option for line stroke style |
| <a id="data"></a> `data` | [`LineSeriesData`](LineSeriesData.md)\<`T`\>[] | - |
| <a id="datalabels"></a> `dataLabels?` | `object` | Options for the series data labels, appearing next to each data point. |
| `dataLabels.allowOverlap?` | `boolean` | **Default** `false` |
| `dataLabels.enabled?` | `boolean` | Enable or disable the data labels **Default** `true` |
| `dataLabels.html?` | `boolean` | Allows to use any html-tags to display the content. The element will be displayed outside the box of the SVG element. **Default** `false` |
| `dataLabels.padding?` | `number` | **Default** `5` |
| `dataLabels.style?` | `Partial`\<[`BaseTextStyle`](../../General/interfaces/BaseTextStyle.md)\> | - |
| <a id="legend"></a> `legend?` | [`ChartLegend`](../../../Configuration/interfaces/ChartLegend.md) & `object` | Individual series legend options. Has higher priority than legend options in widget data |
| <a id="linecap"></a> `linecap?` | `"square"` \| `"butt"` \| `"round"` \| `"none"` | Option for line cap style |
| <a id="linewidth"></a> `lineWidth?` | `number` | Pixel width of the graph line. **Default** `1` |
| <a id="marker"></a> `marker?` | [`PointMarkerOptions`](../../Visual/interfaces/PointMarkerOptions.md) | Options for the point markers of line series |
| <a id="name"></a> `name` | `string` | The name of the series (used in legend, tooltip etc) |
| <a id="opacity"></a> `opacity?` | `number` | Individual opacity for the line. |
| <a id="type"></a> `type` | `"line"` | - |
| <a id="visible"></a> `visible?` | `boolean` | Initial visibility of the series |
| <a id="yaxis"></a> `yAxis?` | `number` | Y-axis index (when using two axes) |
