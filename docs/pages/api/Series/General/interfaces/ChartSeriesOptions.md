[API](../../../overview.md) / [Series/General](../overview.md) / ChartSeriesOptions

Defined in: [src/types/chart/series.ts:74](https://github.com/gravity-ui/charts/blob/6aea3bcf86facdd4a019a7e612d7ac7e27006c35/src/types/chart/series.ts#L74)

## Properties

| Property | Type | Description |
| ------ | ------ | ------ |
| <a id="area"></a> `area?` | `object` | - |
| `area.lineWidth?` | `number` | Pixel width of the graph line. **Default** `1` |
| `area.marker?` | [`PointMarkerOptions`](../../Visual/interfaces/PointMarkerOptions.md) | Options for the point markers of line series |
| `area.states?` | `object` | Options for the series states that provide additional styling information to the series. |
| `area.states.hover?` | [`BasicHoverState`](BasicHoverState.md) & `object` | - |
| `area.states.inactive?` | [`BasicInactiveState`](BasicInactiveState.md) | - |
| <a id="bar-x"></a> `bar-x?` | `object` | - |
| `bar-x.barMaxWidth?` | `number` | The maximum allowed pixel width for a column. This prevents the columns from becoming too wide when there is a small number of points in the chart. **Default** `50` |
| `bar-x.barPadding?` | `number` | Padding between each column or bar, in x axis units. **Default** `0.1` |
| `bar-x.borderRadius?` | `number` | The corner radius of the border surrounding each bar. **Default** `0` |
| `bar-x.dataSorting?` | `object` | - |
| `bar-x.dataSorting.direction?` | `"asc"` \| `"desc"` | Sorting direction. **Default** `'asc'` |
| `bar-x.dataSorting.key?` | `"y"` \| `"name"` | Determines what data value should be used to sort by. Possible values are undefined to disable, "name" to sort by series name or "y" **Default** `undefined` |
| `bar-x.groupPadding?` | `number` | Padding between each value groups, in x axis units **Default** `0.2` |
| `bar-x.states?` | `object` | Options for the series states that provide additional styling information to the series. |
| `bar-x.states.hover?` | [`BasicHoverState`](BasicHoverState.md) | - |
| `bar-x.states.inactive?` | [`BasicInactiveState`](BasicInactiveState.md) | - |
| <a id="bar-y"></a> `bar-y?` | `object` | - |
| `bar-y.barMaxWidth?` | `number` | The maximum allowed pixel width for a column. This prevents the columns from becoming too wide when there is a small number of points in the chart. **Default** `50` |
| `bar-y.barPadding?` | `number` | Padding between each column or bar, in x axis units. **Default** `0.1` |
| `bar-y.dataSorting?` | `object` | - |
| `bar-y.dataSorting.direction?` | `"asc"` \| `"desc"` | Sorting direction. **Default** `'asc'` |
| `bar-y.dataSorting.key?` | `"x"` \| `"name"` | Determines what data value should be used to sort by. Possible values are undefined to disable, "name" to sort by series name or "x" **Default** `undefined` |
| `bar-y.groupPadding?` | `number` | Padding between each value groups, in x axis units **Default** `0.2` |
| `bar-y.states?` | `object` | Options for the series states that provide additional styling information to the series. |
| `bar-y.states.hover?` | [`BasicHoverState`](BasicHoverState.md) | - |
| `bar-y.states.inactive?` | [`BasicInactiveState`](BasicInactiveState.md) | - |
| <a id="datalabels"></a> `dataLabels?` | `object` | Individual data label for each point. |
| `dataLabels.enabled?` | `boolean` | Enable or disable the data labels |
| `dataLabels.renderer?` | (`args`: [`DataLabelRendererData`](DataLabelRendererData.md)) => `SVGTextElementAttributes`\<`SVGTextElement`\> | Callback function to render the data label |
| <a id="line"></a> `line?` | `object` | - |
| `line.dashStyle?` | `"Dash"` \| `"DashDot"` \| `"Dot"` \| `"LongDash"` \| `"LongDashDot"` \| `"LongDashDotDot"` \| `"ShortDash"` \| `"ShortDashDot"` \| `"ShortDashDotDot"` \| `"ShortDot"` \| `"Solid"` | Options for line style **Default** `'Solid'` |
| `line.linecap?` | `"square"` \| `"butt"` \| `"round"` \| `"none"` | Options for line cap style **Default** `'round' when dashStyle is not 'solid', 'none' when dashStyle is not 'solid'` |
| `line.lineWidth?` | `number` | Pixel width of the graph line. **Default** `1` |
| `line.marker?` | [`PointMarkerOptions`](../../Visual/interfaces/PointMarkerOptions.md) | Options for the point markers of line series |
| `line.states?` | `object` | Options for the series states that provide additional styling information to the series. |
| `line.states.hover?` | [`BasicHoverState`](BasicHoverState.md) & `object` | - |
| `line.states.inactive?` | [`BasicInactiveState`](BasicInactiveState.md) | - |
| <a id="pie"></a> `pie?` | `object` | - |
| `pie.states?` | `object` | Options for the series states that provide additional styling information to the series. |
| `pie.states.hover?` | [`BasicHoverState`](BasicHoverState.md) & `object` | - |
| `pie.states.inactive?` | [`BasicInactiveState`](BasicInactiveState.md) | - |
| <a id="scatter"></a> `scatter?` | `object` | - |
| `scatter.states?` | `object` | Options for the series states that provide additional styling information to the series. |
| `scatter.states.hover?` | [`BasicHoverState`](BasicHoverState.md) & `object` | - |
| `scatter.states.inactive?` | [`BasicInactiveState`](BasicInactiveState.md) | - |
| <a id="treemap"></a> `treemap?` | `object` | - |
| `treemap.states?` | `object` | Options for the series states that provide additional styling information to the series. |
| `treemap.states.hover?` | [`BasicHoverState`](BasicHoverState.md) | - |
| `treemap.states.inactive?` | [`BasicInactiveState`](BasicInactiveState.md) | - |
| <a id="waterfall"></a> `waterfall?` | `object` | - |
| `waterfall.barMaxWidth?` | `number` | The maximum allowed pixel width for a column. This prevents the columns from becoming too wide when there is a small number of points in the chart. **Default** `50` |
| `waterfall.barPadding?` | `number` | Padding between each column or bar, in x axis units. **Default** `0.1` |
| `waterfall.states?` | `object` | Options for the series states that provide additional styling information to the series. |
| `waterfall.states.hover?` | [`BasicHoverState`](BasicHoverState.md) | - |
| `waterfall.states.inactive?` | [`BasicInactiveState`](BasicInactiveState.md) | - |
