[Gameplay](../modules/Gameplay.Gameplay.md) / Stance

# Stance <Badge type="tip" text="Class" /> <Score text="Stance" />

姿态

## Hierarchy

- **`Stance`**

  ↳ [`SubStance`](Gameplay.SubStance.md)

## Table of contents

| Methods |
| :-----|
| **[play](Gameplay.Stance.md#play)**(): `boolean` <br> 播放这个姿态对象, 并返回执行结果|
| **[playInternal](Gameplay.Stance.md#playinternal)**(): `boolean` <br> 播放姿态的内部实现|
| **[stop](Gameplay.Stance.md#stop)**(): `boolean` <br> 停止这个姿态对象, 并返回执行结果|
| **[stopInternal](Gameplay.Stance.md#stopinternal)**(): `boolean` <br> 停止姿态的内部实现|

构造函数

**`Effect`**

双端函数

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `character` | [`CharacterBase`](Gameplay.CharacterBase.md) | 角色 |
| `sync` | `boolean` | 是否自动同步 |

## Methods

### play <Score text="play" /> 

▸ **play**(): `boolean` <Badge type="tip" text="other" />

播放这个姿态对象, 并返回执行结果

可选同步

::: warning Precautions

这个操作是否会自动同步多端, 取决于调用Character.loadStance()时传入的sync参数.
返回的执行结果, 在不自动同步时多数情况下可靠;
在自动同步时完全不可靠, 总是会返回true, 因为无法判断其他端的执行情况

:::

#### Returns

`boolean`

是否执行成功

___

### playInternal <Score text="playInternal" /> 

▸ `Protected` **playInternal**(): `boolean` <Badge type="tip" text="other" />

播放姿态的内部实现


#### Returns

`boolean`

是否执行成功

___

### stop <Score text="stop" /> 

▸ **stop**(): `boolean` <Badge type="tip" text="other" />

停止这个姿态对象, 并返回执行结果

可选同步

::: warning Precautions

这个操作是否会自动同步多端, 取决于调用Character.loadStance()时传入的sync参数.
返回的执行结果, 在不自动同步时多数情况下可靠;
在自动同步时完全不可靠, 总是会返回true, 因为无法判断其他端的执行情况.

:::

#### Returns

`boolean`

是否执行成功

___

### stopInternal <Score text="stopInternal" /> 

▸ **stopInternal**(): `boolean` <Badge type="tip" text="other" />

停止姿态的内部实现


#### Returns

`boolean`

是否执行成功
