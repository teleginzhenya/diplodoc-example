[API](../../overview.md) / [Configuration](../overview.md) / ChartData

Defined in: [src/types/index.ts:30](https://github.com/gravity-ui/charts/blob/6aea3bcf86facdd4a019a7e612d7ac7e27006c35/src/types/index.ts#L30)

## Type Parameters

| Type Parameter | Default type |
| ------ | ------ |
| `T` | [`MeaningfulAny`](../../Utilities/type-aliases/MeaningfulAny.md) |

## Properties

| Property | Type | Description |
| ------ | ------ | ------ |
| <a id="chart"></a> `chart?` | [`ChartOptions`](ChartOptions.md) | General options for the chart. |
| <a id="legend"></a> `legend?` | [`ChartLegend`](ChartLegend.md) | The legend displays a labeled box for each data element in the chart. It shows a distinctive symbol paired with a name for every series. |
| <a id="series"></a> `series` | `object` | Represents the series data and series options. |
| `series.data` | [`ChartSeries`](../../Series/General/type-aliases/ChartSeries.md)\<`T`\>[] | Contains data points to be plotted. |
| `series.options?` | [`ChartSeriesOptions`](../../Series/General/interfaces/ChartSeriesOptions.md) | Allows for customizing the appearance and behavior of the series. |
| <a id="split"></a> `split?` | [`ChartSplit`](ChartSplit.md) | Setting for displaying charts on different plots. It can be used to visualize related information on multiple charts. |
| <a id="title"></a> `title?` | [`ChartTitle`](ChartTitle.md) | The main title of the chart. |
| <a id="tooltip"></a> `tooltip?` | [`ChartTooltip`](ChartTooltip.md)\<`T`\> | Options for the tooltip that appears when the user hovers over a series or point. |
| <a id="xaxis"></a> `xAxis?` | [`ChartXAxis`](ChartXAxis.md) | Options for the the X axis. |
| <a id="yaxis"></a> `yAxis?` | [`ChartYAxis`](ChartYAxis.md)[] | Options for the the Y axis or multiple Y axes. |
