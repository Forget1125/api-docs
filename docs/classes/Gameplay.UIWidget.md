[Gameplay](../modules/Gameplay.Gameplay.md) / UIWidget

# UIWidget <Badge type="tip" text="Class" /> <Score text="UIWidget" />

世界UI组件

## Hierarchy

- [`GameObject`](Gameplay.GameObject.md)

  ↳ **`UIWidget`**

## Table of contents

| Accessors |
| :-----|
| **[cylinderArcAngle](Gameplay.UIWidget.md#cylinderarcangle)**(): `number` <br> 获取圆柱体弧形角度|
| **[distanceScaleFactor](Gameplay.UIWidget.md#distancescalefactor)**(): `number` <br> 获取缩放距离系数|
| **[drawSize](Gameplay.UIWidget.md#drawsize)**(): [`Vector2`](Type.Vector2.md) <br> 获取实际渲染大小|
| **[geometryMode](Gameplay.UIWidget.md#geometrymode)**(): [`WidgetGeometryMode`](../enums/Gameplay.WidgetGeometryMode.md) <br> 获取几何体模式|
| **[headUIMaxVisibleDistance](Gameplay.UIWidget.md#headuimaxvisibledistance)**(): `number` <br> 获取最大头顶UI可见距离|
| **[hideByDistanceEnable](Gameplay.UIWidget.md#hidebydistanceenable)**(): `boolean` <br> 获取是否启用最大可见距离|
| **[interaction](Gameplay.UIWidget.md#interaction)**(): `boolean` <br> 获取世界UI交互状态|
| **[isEnemy](Gameplay.UIWidget.md#isenemy)**(): `boolean` <br> 获取是否作为敌方玩家，敌方玩家不显示头顶UI|
| **[occlusionEnable](Gameplay.UIWidget.md#occlusionenable)**(): `boolean` <br> 获取是否可被遮挡|
| **[pivot](Gameplay.UIWidget.md#pivot)**(): [`Vector2`](Type.Vector2.md) <br> 获取锚点位置|
| **[scaledByDistanceEnable](Gameplay.UIWidget.md#scaledbydistanceenable)**(): `boolean` <br> 获取是否开启近大远小|
| **[selfOcclusion](Gameplay.UIWidget.md#selfocclusion)**(): `boolean` <br> 获取是否可被自己遮挡|
| **[widgetSpace](Gameplay.UIWidget.md#widgetspace)**(): [`WidgetSpaceMode`](../enums/Gameplay.WidgetSpaceMode.md) <br> 获取显示方式|


::: details 点击查看继承
| Accessors |
| :-----|
| **[forwardVector](Gameplay.GameObject.md#forwardvector)**(): [`Vector`](Type.Vector.md) <br> 获取当前物体的向前向量|
| **[guid](Gameplay.GameObject.md#guid)**(): `string` <br> 获取对象的GUID（唯一标识一个对象的字符串）。|
| **[lockStatus](Gameplay.GameObject.md#lockstatus)**(): `boolean` <br> 获取对象是否锁定|
| **[name](Gameplay.GameObject.md#name)**(): `string` <br> 返回当前物体名称|
| **[netStatus](Gameplay.GameObject.md#netstatus)**(): [`NetStatus`](../enums/Type.NetStatus.md) <br> 获取当前物体同步状态|
| **[parent](Gameplay.GameObject.md#parent)**(): `GameObject` <br> 获取当前父物体|
| **[relativeLocation](Gameplay.GameObject.md#relativelocation)**(): [`Vector`](Type.Vector.md) <br> 获取相对位置|
| **[relativeRotation](Gameplay.GameObject.md#relativerotation)**(): [`Rotation`](Type.Rotation.md) <br> 获取相对旋转|
| **[relativeScale](Gameplay.GameObject.md#relativescale)**(): [`Vector`](Type.Vector.md) <br> 获取相对缩放|
| **[rightVector](Gameplay.GameObject.md#rightvector)**(): [`Vector`](Type.Vector.md) <br> 获取当前物体的向右向量|
| **[staticStatus](Gameplay.GameObject.md#staticstatus)**(): `boolean` <br> 获取对象是否静态|
| **[tag](Gameplay.GameObject.md#tag)**(): `string` <br> 获取当前物体的Tag|
| **[transform](Gameplay.GameObject.md#transform)**(): [`Transform`](Type.Transform.md) <br> 返回当前物体transform|
| **[upVector](Gameplay.GameObject.md#upvector)**(): [`Vector`](Type.Vector.md) <br> 获取当前物体的向上向量|
| **[useUpdate](Gameplay.GameObject.md#useupdate)**(): `boolean` <br> 获取对象是否使用更新|
| **[visible](Gameplay.GameObject.md#visible)**(): `boolean` <br> since:v0.20.0 reason:api重构 replacement:getVisibility()|
| **[worldLocation](Gameplay.GameObject.md#worldlocation)**(): [`Vector`](Type.Vector.md) <br> 获取物体的世界坐标|
| **[worldRotation](Gameplay.GameObject.md#worldrotation)**(): [`Rotation`](Type.Rotation.md) <br> 获取物体的世界旋转|
| **[worldScale](Gameplay.GameObject.md#worldscale)**(): [`Vector`](Type.Vector.md) <br> 获取物体的世界缩放|
:::


| Methods |
| :-----|
| **[getUI](Gameplay.UIWidget.md#getui)**(): [`UserWidget`](UI.UserWidget.md) <br> 获取UI对象|
| **[refresh](Gameplay.UIWidget.md#refresh)**(): `void` <br> 请求重新绘制|
| **[setTargetUIWidget](Gameplay.UIWidget.md#settargetuiwidget)**([`UserWidget`](UI.UserWidget.md)): `void` <br> 设置UI|
| **[setUI](Gameplay.UIWidget.md#setui)**(`string`): `void` <br> 通过GUID设置UI|


::: details 点击查看继承
| Methods |
| :-----|
| **[addDestroyCallback](Gameplay.GameObject.md#adddestroycallback)**((...`arg`: `unknown`[]) => `void`): `void` <br> 添加物体Destroy事件回调|
| **[asyncGetScriptByName](Gameplay.GameObject.md#asyncgetscriptbyname)**(`string`): `Promise`<`Script`\> <br> 异步获得当前物体下的指定脚本 客户端不维系父子关系|
| **[attachToGameObject](Gameplay.GameObject.md#attachtogameobject)**(`GameObject`): `void` <br> 将物体附着到指定物体上|
| **[clone](Gameplay.GameObject.md#clone)**(`boolean`): `GameObject` <br> 复制对象|
| **[deleteDestroyCallback](Gameplay.GameObject.md#deletedestroycallback)**((...`arg`: `unknown`[]) => `void`): `void` <br> 移除物体Destroy事件回调|
| **[destroy](Gameplay.GameObject.md#destroy)**(): `void` <br> 删除对象|
| **[detachFromGameObject](Gameplay.GameObject.md#detachfromgameobject)**(): `void` <br> 将此物体与当前附着的物体分离|
| **[getBoundingBoxSize](Gameplay.GameObject.md#getboundingboxsize)**(`boolean`, `boolean`, [`Vector`](Type.Vector.md)): [`Vector`](Type.Vector.md) <br> 获取物体包围盒大小|
| **[getBounds](Gameplay.GameObject.md#getbounds)**(`boolean`, [`Vector`](Type.Vector.md), [`Vector`](Type.Vector.md), `boolean`): `void` <br> 获取GameObject边界|
| **[getChildByGuid](Gameplay.GameObject.md#getchildbyguid)**(`string`): `GameObject` <br> 根据GUID查找子物体|
| **[getChildByName](Gameplay.GameObject.md#getchildbyname)**(`string`): `GameObject` <br> 根据名称查找子物体|
| **[getChildren](Gameplay.GameObject.md#getchildren)**(): `GameObject`[] <br> 获取Children，客户端不维系父子关系。推荐使用Find替代|
| **[getChildrenBoxCenter](Gameplay.GameObject.md#getchildrenboxcenter)**([`Vector`](Type.Vector.md)): [`Vector`](Type.Vector.md) <br> 获取所有子对象包围盒中心点(不包含父对象,父对象不可用返回[0,0,0])|
| **[getCollision](Gameplay.GameObject.md#getcollision)**(): [`PropertyStatus`](../enums/Type.PropertyStatus.md) \| [`CollisionStatus`](../enums/Type.CollisionStatus.md) <br> 返回碰撞状态|
| **[getForwardVector](Gameplay.GameObject.md#getforwardvector)**([`Vector`](Type.Vector.md)): [`Vector`](Type.Vector.md) <br> 获取当前物体的向前向量|
| **[getRelativeLocation](Gameplay.GameObject.md#getrelativelocation)**([`Vector`](Type.Vector.md)): [`Vector`](Type.Vector.md) <br> 获取相对位置|
| **[getRelativeRotation](Gameplay.GameObject.md#getrelativerotation)**([`Rotation`](Type.Rotation.md)): [`Rotation`](Type.Rotation.md) <br> 获取相对旋转|
| **[getRelativeScale](Gameplay.GameObject.md#getrelativescale)**([`Vector`](Type.Vector.md)): [`Vector`](Type.Vector.md) <br> 获取相对缩放|
| **[getRightVector](Gameplay.GameObject.md#getrightvector)**([`Vector`](Type.Vector.md)): [`Vector`](Type.Vector.md) <br> 获取当前物体的向右向量|
| **[getScriptByGuid](Gameplay.GameObject.md#getscriptbyguid)**(`string`): `Script` <br> 获得当前物体下的指定脚本 客户端不维系父子关系 推荐使用Find替代|
| **[getScriptByName](Gameplay.GameObject.md#getscriptbyname)**(`string`): `Script` <br> 获得当前物体下的指定脚本 客户端不维系父子关系 推荐使用Find替代|
| **[getScripts](Gameplay.GameObject.md#getscripts)**(): `Script`[] <br> 获得当前物体下的所有脚本 客户端不维系父子关系 推荐使用Find替代|
| **[getSourceAssetGuid](Gameplay.GameObject.md#getsourceassetguid)**(): `string` <br> 获取当前物体使用资源的GUID|
| **[getTransform](Gameplay.GameObject.md#gettransform)**([`Transform`](Type.Transform.md)): [`Transform`](Type.Transform.md) <br> 返回当前物体Transform|
| **[getUpVector](Gameplay.GameObject.md#getupvector)**([`Vector`](Type.Vector.md)): [`Vector`](Type.Vector.md) <br> 获取当前物体的向上向量|
| **[getVisibility](Gameplay.GameObject.md#getvisibility)**(): `boolean` <br> 获取GameObject是否被显示|
| **[getWorldLocation](Gameplay.GameObject.md#getworldlocation)**([`Vector`](Type.Vector.md)): [`Vector`](Type.Vector.md) <br> 获取物体的世界坐标|
| **[getWorldRotation](Gameplay.GameObject.md#getworldrotation)**([`Rotation`](Type.Rotation.md)): [`Rotation`](Type.Rotation.md) <br> 获取物体的世界旋转|
| **[getWorldScale](Gameplay.GameObject.md#getworldscale)**([`Vector`](Type.Vector.md)): [`Vector`](Type.Vector.md) <br> 获取物体的世界缩放|
| **[isRunningClient](Gameplay.GameObject.md#isrunningclient)**(): `boolean` <br> 是否为客户端|
| **[onDestroy](Gameplay.GameObject.md#ondestroy)**(): `void` <br> 周期函数 被销毁时调用|
| **[onStart](Gameplay.GameObject.md#onstart)**(): `void` <br> 周期函数 脚本开始执行时调用|
| **[onUpdate](Gameplay.GameObject.md#onupdate)**(`number`): `void` <br> 周期函数 useUpdate 设置为 true 后,每帧被执行,设置为false,不会执行|
| **[ready](Gameplay.GameObject.md#ready)**(): `Promise`<[`GameObject`](Gameplay.GameObject.md)\> <br> GameObject准备好后返回|
| **[setCollision](Gameplay.GameObject.md#setcollision)**([`PropertyStatus`](../enums/Type.PropertyStatus.md) \, `boolean`): `void` <br> 设置碰撞状态|
| **[setLocationAndRotation](Gameplay.GameObject.md#setlocationandrotation)**([`Vector`](Type.Vector.md), [`Rotation`](Type.Rotation.md)): `void` <br> 同时设置物体的世界位置与旋转|
| **[setRelativeLocation](Gameplay.GameObject.md#setrelativelocation)**([`Vector`](Type.Vector.md)): `void` <br> 设置相对位置|
| **[setRelativeRotation](Gameplay.GameObject.md#setrelativerotation)**([`Rotation`](Type.Rotation.md)): `void` <br> 设置相对旋转|
| **[setRelativeScale](Gameplay.GameObject.md#setrelativescale)**([`Vector`](Type.Vector.md)): `void` <br> 设置相对缩放|
| **[setTransform](Gameplay.GameObject.md#settransform)**([`Transform`](Type.Transform.md)): `void` <br> 设置当前物体transform|
| **[setVisibility](Gameplay.GameObject.md#setvisibility)**([`PropertyStatus`](../enums/Type.PropertyStatus.md), `boolean`): `void` <br> 设置GameObject是否被显示|
| **[setWorldLocation](Gameplay.GameObject.md#setworldlocation)**([`Vector`](Type.Vector.md)): `void` <br> 设置物体的世界坐标|
| **[setWorldRotation](Gameplay.GameObject.md#setworldrotation)**([`Rotation`](Type.Rotation.md)): `void` <br> 设置物体的世界旋转|
| **[setWorldScale](Gameplay.GameObject.md#setworldscale)**([`Vector`](Type.Vector.md)): `void` <br> 设置物体的世界缩放|
| **[asyncFind](Gameplay.GameObject.md#asyncfind)**(`string`): `Promise`<`GameObject`\> <br> 通过GUID异步查找GameObject,默认是五秒,可以通过 `core.setGlobalAsyncOverTime(5000);|
| **[asyncSpawnGameObject](Gameplay.GameObject.md#asyncspawngameobject)**(`string`, `boolean`): `Promise`<`GameObject`\> <br> 异步构造一个 GameObject 资源不存在会先去下载资源再去创建|
| **[find](Gameplay.GameObject.md#find)**(`string`): `GameObject` <br> 通过GUID查找GameObject|
| **[findGameObjectByTag](Gameplay.GameObject.md#findgameobjectbytag)**(`string`): `GameObject`[] <br> 通过自定义Tag获取GameObject|
| **[getGameObjectByName](Gameplay.GameObject.md#getgameobjectbyname)**(`string`): `GameObject` <br> 通过名字查找物体|
| **[getGameObjectsByName](Gameplay.GameObject.md#getgameobjectsbyname)**(`string`): `GameObject`[] <br> 通过名字查找物体|
| **[spawnGameObject](Gameplay.GameObject.md#spawngameobject)**(`string`, `boolean`): `GameObject` <br> 构造一个 GameObject|
:::


## Accessors

### cylinderArcAngle <Score text="cylinderArcAngle" /> 

• `get` **cylinderArcAngle**(): `number`

获取圆柱体弧形角度

#### Returns

`number`

角度

• `set` **cylinderArcAngle**(`inCylinderArcAngle`): `void`

设置圆柱体弧形角度

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `inCylinderArcAngle` | `number` | 角度 |


___

### distanceScaleFactor <Score text="distanceScaleFactor" /> 

• `get` **distanceScaleFactor**(): `number`

获取缩放距离系数

#### Returns

`number`

距离系数

• `set` **distanceScaleFactor**(`Value`): `void`

设置缩放距离系数

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `Value` | `number` | 距离系数 |


___

### drawSize <Score text="drawSize" /> 

• `get` **drawSize**(): [`Vector2`](Type.Vector2.md)

获取实际渲染大小

#### Returns

[`Vector2`](Type.Vector2.md)

渲染大小2D

• `set` **drawSize**(`newSize`): `void`

设置实际渲染大小

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `newSize` | [`Vector2`](Type.Vector2.md) | 渲染大小2D |



### geometryMode <Score text="geometryMode" /> 

• `get` **geometryMode**(): [`WidgetGeometryMode`](../enums/Gameplay.WidgetGeometryMode.md)

获取几何体模式

#### Returns

[`WidgetGeometryMode`](../enums/Gameplay.WidgetGeometryMode.md)

几何体模式枚举

• `set` **geometryMode**(`inGeometryMode`): `void`

设置几何体模式

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `inGeometryMode` | [`WidgetGeometryMode`](../enums/Gameplay.WidgetGeometryMode.md) | 几何体模式枚举 |



### headUIMaxVisibleDistance <Score text="headUIMaxVisibleDistance" /> 

• `get` **headUIMaxVisibleDistance**(): `number`

获取最大头顶UI可见距离

#### Returns

`number`

可见距离

• `set` **headUIMaxVisibleDistance**(`Value`): `void`

设置最大头顶UI可见距离

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `Value` | `number` | 可见距离 |


___

### hideByDistanceEnable <Score text="hideByDistanceEnable" /> 

• `get` **hideByDistanceEnable**(): `boolean`

获取是否启用最大可见距离

#### Returns

`boolean`

true：开启

• `set` **hideByDistanceEnable**(`Value`): `void`

设置是否启用最大可见距离

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `Value` | `boolean` | 布尔值 |


___

### interaction <Score text="interaction" /> 

• `get` **interaction**(): `boolean` <Badge type="tip" text="other" />

获取世界UI交互状态

::: warning Precautions

对世界UI，头顶UI生效

:::

客户端生效

#### Returns

`boolean`

是否可交互

• `set` **interaction**(`inInteraction`): `void` <Badge type="tip" text="other" />

设置世界UI交互状态

::: warning Precautions

对世界UI，头顶UI生效

:::

客户端生效

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `inInteraction` | `boolean` | 是否可交互 |


是否设置成功

___

### isEnemy <Score text="isEnemy" /> 

• `get` **isEnemy**(): `boolean`

获取是否作为敌方玩家，敌方玩家不显示头顶UI

#### Returns

`boolean`

布尔值

• `set` **isEnemy**(`Value`): `void`

设置是否作为敌方玩家，敌方玩家不显示头顶UI

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `Value` | `boolean` | 布尔值 |



### occlusionEnable <Score text="occlusionEnable" /> 

• `get` **occlusionEnable**(): `boolean`

获取是否可被遮挡

#### Returns

`boolean`

true：可被遮挡

• `set` **occlusionEnable**(`Value`): `void`

设置是否可被遮挡

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `Value` | `boolean` | 布尔值 |



### pivot <Score text="pivot" /> 

• `get` **pivot**(): [`Vector2`](Type.Vector2.md)

获取锚点位置

#### Returns

[`Vector2`](Type.Vector2.md)

位置信息

• `set` **pivot**(`position`): `void`

设置锚点位置

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `position` | [`Vector2`](Type.Vector2.md) | 位置信息 |



### scaledByDistanceEnable <Score text="scaledByDistanceEnable" /> 

• `get` **scaledByDistanceEnable**(): `boolean`

获取是否开启近大远小

#### Returns

`boolean`

true：开启

• `set` **scaledByDistanceEnable**(`Value`): `void`

设置是否开启近大远小

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `Value` | `boolean` | 布尔值 |


___

### selfOcclusion <Score text="selfOcclusion" /> 

• `get` **selfOcclusion**(): `boolean`

获取是否可被自己遮挡

#### Returns

`boolean`

布尔值

• `set` **selfOcclusion**(`Value`): `void`

设置是否可被自己遮挡

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `Value` | `boolean` | 布尔值 |



### widgetSpace <Score text="widgetSpace" /> 

• `get` **widgetSpace**(): [`WidgetSpaceMode`](../enums/Gameplay.WidgetSpaceMode.md)

获取显示方式

#### Returns

[`WidgetSpaceMode`](../enums/Gameplay.WidgetSpaceMode.md)

显示方式枚举

• `set` **widgetSpace**(`newSpace`): `void`

设置显示方式

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `newSpace` | [`WidgetSpaceMode`](../enums/Gameplay.WidgetSpaceMode.md) | 显示方式 |



## Methods

### getUI <Score text="getUI" /> 

▸ **getUI**(): [`UserWidget`](UI.UserWidget.md) <Badge type="tip" text="other" />

获取UI对象

客户端生效

#### Returns

[`UserWidget`](UI.UserWidget.md)

UI对象


### refresh <Score text="refresh" /> 

▸ **refresh**(): `void` <Badge type="tip" text="other" />

请求重新绘制

客户端生效



### setTargetUIWidget <Score text="setTargetUIWidget" /> 

▸ **setTargetUIWidget**(`uiUserWidget`): `void` <Badge type="tip" text="other" />

设置UI

客户端生效

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `uiUserWidget` | [`UserWidget`](UI.UserWidget.md) | UI对象 |



### setUI <Score text="setUI" /> 

▸ **setUI**(`GUID`): `void` <Badge type="tip" text="other" />

通过GUID设置UI

客户端生效

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `GUID` | `string` | UI的GUID |

