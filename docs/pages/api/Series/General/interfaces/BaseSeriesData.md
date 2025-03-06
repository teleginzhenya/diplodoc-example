[API](../../../overview.md) / [Series/General](../overview.md) / BaseSeriesData

Defined in: [src/types/chart/base.ts:36](https://github.com/gravity-ui/charts/blob/6aea3bcf86facdd4a019a7e612d7ac7e27006c35/src/types/chart/base.ts#L36)

## Extended by

- [`AreaSeriesData`](../../Area/interfaces/AreaSeriesData.md)
- [`BarXSeriesData`](../../Bar-X/interfaces/BarXSeriesData.md)
- [`BarYSeriesData`](../../Bar-Y/interfaces/BarYSeriesData.md)
- [`LineSeriesData`](../../Line/interfaces/LineSeriesData.md)
- [`PieSeriesData`](../../Pie/interfaces/PieSeriesData.md)
- [`ScatterSeriesData`](../../Scatter/interfaces/ScatterSeriesData.md)
- [`TreemapSeriesData`](../../Treemap/interfaces/TreemapSeriesData.md)
- [`WaterfallSeriesData`](../../Waterfall/interfaces/WaterfallSeriesData.md)

## Type Parameters

| Type Parameter | Default type |
| ------ | ------ |
| `T` | [`MeaningfulAny`](../../../Utilities/type-aliases/MeaningfulAny.md) |

## Properties

| Property | Type | Description |
| ------ | ------ | ------ |
| <a id="color"></a> `color?` | `string` | Individual color for the data chunk (point in scatter, segment in pie, bar etc) |
| <a id="custom"></a> `custom?` | `T` | A reserved subspace to store options and values for customized functionality Here you can add additional data for your own event callbacks and formatter callbacks |
