[API](../../../overview.md) / [Series/Area](../overview.md) / AreaSeriesData

Defined in: [src/types/chart/area.ts:8](https://github.com/gravity-ui/charts/blob/6aea3bcf86facdd4a019a7e612d7ac7e27006c35/src/types/chart/area.ts#L8)

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
| <a id="label"></a> `label?` | `string` \| `number` | Data label value of the point. If not specified, the y value is used. |
| <a id="marker"></a> `marker?` | `object` | Individual marker options for the point. |
| `marker.states?` | `object` | States for a single point marker. |
| `marker.states.normal?` | `object` | The normal state of a single point marker. |
| `marker.states.normal.enabled` | `boolean` | Enable or disable the point marker. **Default** `false` |
| <a id="x"></a> `x?` | `string` \| `number` | The `x` value of the point. Depending on the context , it may represents: - numeric value (for `linear` x axis) - timestamp value (for `datetime` x axis) - x axis category value (for `category` x axis). If the type is a string, then it is a category value itself. If the type is a number, then it is the index of an element in the array of categories described in `xAxis.categories` |
| <a id="y"></a> `y?` | `string` \| `number` | The `y` value of the point. Depending on the context , it may represents: - numeric value (for `linear` y axis) - timestamp value (for `datetime` y axis) - y axis category value (for `category` y axis). If the type is a string, then it is a category value itself. If the type is a number, then it is the index of an element in the array of categories described in `yAxis[0].categories` |
