## 目录

### Interfaces（接口）
- [Item](https://cloud.tencent.com/document/product/1484/75805)

### Variables（变量）
- [default](#default)

## Variables（变量）
[](id:default)
### default
`Const` **default**: `Object`
```
Defined in typings/dataset.d.ts:17
```


#### Type declaration
| Name | Type |
| :------ | :------ |
| `add` | (`filename`: `string`, `values`: `Record`<`string`, `any`\>[]) => `void` |
| `forEach` | (`fileName`: `string`, `callback`: (`item`: [`Item`](../interfaces/dataset.Item.md), `i?`: `number`) => `void`) => `void` |
| `get` | (`key`: `string`) => `string` |
| `random` | (`filename`: `string`) => `Record`<`string`, `any`\> |
