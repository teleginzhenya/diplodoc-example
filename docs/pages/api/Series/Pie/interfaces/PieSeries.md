[API](../../../overview.md) / [Series/Pie](../overview.md) / PieSeries

Defined in: [src/types/chart/pie.ts:27](https://github.com/gravity-ui/charts/blob/6aea3bcf86facdd4a019a7e612d7ac7e27006c35/src/types/chart/pie.ts#L27)

## Extends

- [`BaseSeries`](../../General/interfaces/BaseSeries.md)

## Type Parameters

| Type Parameter | Default type |
| ------ | ------ |
| `T` | [`MeaningfulAny`](../../../Utilities/type-aliases/MeaningfulAny.md) |

## Properties

| Property | Type | Description |
| ------ | ------ | ------ |
| <a id="bordercolor"></a> `borderColor?` | `string` | The color of the border surrounding each segment. **Default** `--g-color-base-background` from @gravity-ui/uikit. |
| <a id="borderradius"></a> `borderRadius?` | `number` | The corner radius of the border surrounding each segment. **Default** `0` |
| <a id="borderwidth"></a> `borderWidth?` | `number` | The width of the border surrounding each segment. **Default** `'1px'` |
| <a id="center"></a> `center?` | \[`null` \| `string` \| `number`, `null` \| `string` \| `number`\] | The center of the pie chart relative to the chart area. |
| <a id="cursor"></a> `cursor?` | `string` | You can set the cursor to "pointer" if you have click events attached to the series, to signal to the user that the points and lines can be clicked. |
| <a id="data"></a> `data` | [`PieSeriesData`](PieSeriesData.md)\<`T`\>[] | - |
| <a id="datalabels"></a> `dataLabels?` | `object` & `object` | Options for the series data labels, appearing next to each data point. |
| <a id="innerradius"></a> `innerRadius?` | `string` \| `number` | The inner radius of the pie. **Default** `0` |
| <a id="legend"></a> `legend?` | [`ChartLegend`](../../../Configuration/interfaces/ChartLegend.md) & `object` | Individual series legend options. Has higher priority than legend options in widget data |
| <a id="radius"></a> `radius?` | `string` \| `number` | The radius of the pie relative to the chart area. The default behaviour is to scale to the chart area. |
| <a id="rendercustomshape"></a> `renderCustomShape?` | (`args`: `object`) => `BaseType` | Function for adding custom svg nodes for a series |
| <a id="type"></a> `type` | `"pie"` | - |
| <a id="visible"></a> `visible?` | `boolean` | Initial visibility of the series |
