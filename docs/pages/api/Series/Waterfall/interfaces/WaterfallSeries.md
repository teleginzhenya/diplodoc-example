[API](../../../overview.md) / [Series/Waterfall](../overview.md) / WaterfallSeries

Defined in: [src/types/chart/waterfall.ts:28](https://github.com/gravity-ui/charts/blob/6aea3bcf86facdd4a019a7e612d7ac7e27006c35/src/types/chart/waterfall.ts#L28)

## Extends

- [`BaseSeries`](../../General/interfaces/BaseSeries.md)

## Type Parameters

| Type Parameter | Default type |
| ------ | ------ |
| `T` | [`MeaningfulAny`](../../../Utilities/type-aliases/MeaningfulAny.md) |

## Properties

| Property | Type | Description |
| ------ | ------ | ------ |
| <a id="color"></a> `color?` | `string` | The main color of the series (hex, rgba). |
| <a id="cursor"></a> `cursor?` | `string` | You can set the cursor to "pointer" if you have click events attached to the series, to signal to the user that the points and lines can be clicked. |
| <a id="data"></a> `data` | [`WaterfallSeriesData`](WaterfallSeriesData.md)\<`T`\>[] | - |
| <a id="datalabels"></a> `dataLabels?` | `object` | Options for the series data labels, appearing next to each data point. |
| `dataLabels.allowOverlap?` | `boolean` | **Default** `false` |
| `dataLabels.enabled?` | `boolean` | Enable or disable the data labels **Default** `true` |
| `dataLabels.html?` | `boolean` | Allows to use any html-tags to display the content. The element will be displayed outside the box of the SVG element. **Default** `false` |
| `dataLabels.padding?` | `number` | **Default** `5` |
| `dataLabels.style?` | `Partial`\<[`BaseTextStyle`](../../General/interfaces/BaseTextStyle.md)\> | - |
| <a id="legend"></a> `legend?` | [`ChartLegend`](../../../Configuration/interfaces/ChartLegend.md) & `object` | Individual series legend options. Has higher priority than legend options in widget data. |
| <a id="name"></a> `name` | `string` | The name of the series (used in legend, tooltip etc). |
| <a id="negativecolor"></a> `negativeColor?` | `string` | The color used for negative values. If it is not specified, the general color of the series is used. |
| <a id="positivecolor"></a> `positiveColor?` | `string` | The color used for positive values. If it is not specified, the general color of the series is used. |
| <a id="type"></a> `type` | `"waterfall"` | - |
| <a id="visible"></a> `visible?` | `boolean` | Initial visibility of the series |
