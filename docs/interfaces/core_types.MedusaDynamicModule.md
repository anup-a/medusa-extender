[medusa-extender](../README.md) / [Exports](../modules.md) / [core/types](../modules/core_types.md) / MedusaDynamicModule

# Interface: MedusaDynamicModule

[core/types](../modules/core_types.md).MedusaDynamicModule

**`interface`**
Describe a dynamic module which resolve its import dynamically.

## Table of contents

### Methods

- [forRoot](core_types.MedusaDynamicModule.md#forroot)

## Methods

### forRoot

▸ **forRoot**<`T`\>(`configModule`): `Promise`<[`ModuleInjectionOptions`](../modules/core_types.md#moduleinjectionoptions)<`unknown`\>\>

#### Type parameters

| Name |
| :------ |
| `T` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `configModule` | `T` |

#### Returns

`Promise`<[`ModuleInjectionOptions`](../modules/core_types.md#moduleinjectionoptions)<`unknown`\>\>

#### Defined in

[src/core/types.ts:187](https://github.com/adrien2p/medusa-extender/blob/e82d041/src/core/types.ts#L187)
