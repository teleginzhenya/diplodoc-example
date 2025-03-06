[API](../../../overview.md) / [Series/Pie](../overview.md) / PieSeriesData

Defined in: [src/types/chart/pie.ts:9](https://github.com/gravity-ui/charts/blob/6aea3bcf86facdd4a019a7e612d7ac7e27006c35/src/types/chart/pie.ts#L9)

## Extends

- [`BaseSeriesData`](../../General/interfaces/BaseSeriesData.md)\<`T`\>

## Type Parameters

| Type Parameter | Default type |
| ------ | ------ |
| `T` | [`MeaningfulAny`](../../../Utilities/type-aliases/MeaningfulAny.md) |

## Properties

| Property | Type | Description |
| ------ | ------ | ------ |
| <a id="color"></a> `color?` | `string` | Individual color for the data chunk (point in scatter, segment in pie, bar etc) |
| <a id="custom"></a> `custom?` | `T` | A reserved subspace to store options and values for customized functionality Here you can add additional data for your own event callbacks and formatter callbacks |
| <a id="label"></a> `label?` | `string` | Initial data label of the pie segment. If not specified, the value is used. |
| <a id="name"></a> `name` | `string` | The name of the pie segment (used in legend, tooltip etc). |
| <a id="opacity"></a> `opacity?` | `number` | Individual opacity for the pie segment. |
| <a id="radius"></a> `radius?` | `string` \| `number` | The individual radius of the pie segment. The default value is series.radius |
| <a id="value"></a> `value` | `number` | The value of the pie segment. |
| <a id="visible"></a> `visible?` | `boolean` | Initial visibility of the pie segment. |
