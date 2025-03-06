[API](../../overview.md) / [Configuration](../overview.md) / ChartAxisLabels

Defined in: [src/types/chart/axis.ts:10](https://github.com/gravity-ui/charts/blob/6aea3bcf86facdd4a019a7e612d7ac7e27006c35/src/types/chart/axis.ts#L10)

## Properties

| Property | Type | Description |
| ------ | ------ | ------ |
| <a id="autorotation"></a> `autoRotation?` | `boolean` | For horizontal axes, enable label rotation to prevent overlapping labels. If there is enough space, labels are not rotated. As the chart gets narrower, it will start rotating the labels -45 degrees. |
| <a id="dateformat"></a> `dateFormat?` | `string` | - |
| <a id="enabled"></a> `enabled?` | `boolean` | Enable or disable the axis labels. |
| <a id="margin"></a> `margin?` | `number` | The label's pixel distance from the perimeter of the plot area. @default: 10 |
| <a id="numberformat"></a> `numberFormat?` | [`FormatNumberOptions`](../../Utilities/interfaces/FormatNumberOptions.md) | - |
| <a id="padding"></a> `padding?` | `number` | The pixel padding for axis labels, to ensure white space between them. @defaults: 5 |
| <a id="rotation"></a> `rotation?` | `number` | Rotation of the labels in degrees. @default: 0 |
| <a id="style"></a> `style?` | `Partial`\<[`BaseTextStyle`](../../Series/General/interfaces/BaseTextStyle.md)\> | - |
