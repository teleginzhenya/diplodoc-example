[API](../../../overview.md) / [Series/Treemap](../overview.md) / TreemapSeries

Defined in: [src/types/chart/treemap.ts:21](https://github.com/gravity-ui/charts/blob/6aea3bcf86facdd4a019a7e612d7ac7e27006c35/src/types/chart/treemap.ts#L21)

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
| <a id="data"></a> `data` | [`TreemapSeriesData`](TreemapSeriesData.md)\<`T`\>[] | - |
| <a id="datalabels"></a> `dataLabels?` | `object` & `object` | Options for the series data labels, appearing next to each data point. |
| <a id="layoutalgorithm"></a> `layoutAlgorithm?` | `"slice"` \| `"binary"` \| `"dice"` \| `"slice-dice"` \| `"squarify"` | - |
| <a id="legend"></a> `legend?` | [`ChartLegend`](../../../Configuration/interfaces/ChartLegend.md) & `object` | Individual series legend options. Has higher priority than legend options in widget data. |
| <a id="levels"></a> `levels?` | `object`[] | Set options on specific levels. Takes precedence over series options, but not point options. |
| <a id="name"></a> `name` | `string` | The name of the series (used in legend, tooltip etc). |
| <a id="type"></a> `type` | `"treemap"` | - |
| <a id="visible"></a> `visible?` | `boolean` | Initial visibility of the series |
