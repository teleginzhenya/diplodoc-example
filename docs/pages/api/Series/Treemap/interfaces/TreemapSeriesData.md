[API](../../../overview.md) / [Series/Treemap](../overview.md) / TreemapSeriesData

Defined in: [src/types/chart/treemap.ts:7](https://github.com/gravity-ui/charts/blob/6aea3bcf86facdd4a019a7e612d7ac7e27006c35/src/types/chart/treemap.ts#L7)

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
| <a id="id"></a> `id?` | `string` | An id for the node. Used to group children. |
| <a id="name"></a> `name` | `string` \| `string`[] | The name of the node (used in legend, tooltip etc). |
| <a id="parentid"></a> `parentId?` | `string` | Parent id. Used to build a tree structure. The value should be the id of the node which is the parent. If no nodes has a matching id, or this option is undefined, then the parent will be set to the root. |
| <a id="value"></a> `value?` | `number` | The value of the node. All nodes should have this property except nodes that have children. |
