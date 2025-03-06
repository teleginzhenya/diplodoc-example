[API](../../../overview.md) / [Series/Bar-X](../overview.md) / BarXSeries

Defined in: [src/types/chart/bar-x.ts:35](https://github.com/gravity-ui/charts/blob/6aea3bcf86facdd4a019a7e612d7ac7e27006c35/src/types/chart/bar-x.ts#L35)

## Extends

- [`BaseSeries`](../../General/interfaces/BaseSeries.md)

## Type Parameters

| Type Parameter | Default type |
| ------ | ------ |
| `T` | [`MeaningfulAny`](../../../Utilities/type-aliases/MeaningfulAny.md) |

## Properties

| Property | Type | Description |
| ------ | ------ | ------ |
| <a id="borderradius"></a> `borderRadius?` | `number` | The corner radius of the border surrounding each bar. **Default** `0` |
| <a id="color"></a> `color?` | `string` | The main color of the series (hex, rgba) |
| <a id="cursor"></a> `cursor?` | `string` | You can set the cursor to "pointer" if you have click events attached to the series, to signal to the user that the points and lines can be clicked. |
| <a id="data"></a> `data` | [`BarXSeriesData`](BarXSeriesData.md)\<`T`\>[] | - |
| <a id="datalabels"></a> `dataLabels?` | `object` & `object` & `object` | Options for the series data labels, appearing next to each data point. |
| <a id="grouping"></a> `grouping?` | `boolean` | Whether to group non-stacked columns or to let them render independent of each other. When false columns will be laid out individually and overlap each other. **Default** `true` |
| <a id="legend"></a> `legend?` | [`ChartLegend`](../../../Configuration/interfaces/ChartLegend.md) & `object` | Individual series legend options. Has higher priority than legend options in widget data |
| <a id="name"></a> `name` | `string` | The name of the series (used in legend, tooltip etc) |
| <a id="stackid"></a> `stackId?` | `string` | This option allows grouping series in a stacked chart |
| <a id="stacking"></a> `stacking?` | `"percent"` \| `"normal"` | Whether to stack the values of each series on top of each other. Possible values are undefined to disable, "normal" to stack by value or "percent" **Default** `undefined` |
| <a id="type"></a> `type` | `"bar-x"` | - |
| <a id="visible"></a> `visible?` | `boolean` | Initial visibility of the series |
| <a id="yaxis"></a> `yAxis?` | `number` | Y-axis index (when using two axes) |
