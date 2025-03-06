[API](../../overview.md) / [Configuration](../overview.md) / ChartTooltip

Defined in: [src/types/chart/tooltip.ts:86](https://github.com/gravity-ui/charts/blob/6aea3bcf86facdd4a019a7e612d7ac7e27006c35/src/types/chart/tooltip.ts#L86)

## Type Parameters

| Type Parameter | Default type |
| ------ | ------ |
| `T` | [`MeaningfulAny`](../../Utilities/type-aliases/MeaningfulAny.md) |

## Properties

| Property | Type | Description |
| ------ | ------ | ------ |
| <a id="enabled"></a> `enabled?` | `boolean` | - |
| <a id="pin"></a> `pin?` | `object` | - |
| `pin.enabled?` | `boolean` | - |
| `pin.modifierKey?` | `"altKey"` \| `"metaKey"` | - |
| <a id="renderer"></a> `renderer?` | (`args`: [`ChartTooltipRendererArgs`](ChartTooltipRendererArgs.md)\<`T`\>) => `null` \| `ReactElement` | Specifies the renderer for the tooltip. If returned null default tooltip renderer will be used. |
