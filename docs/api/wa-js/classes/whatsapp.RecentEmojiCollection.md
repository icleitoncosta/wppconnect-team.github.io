---
id: "whatsapp.RecentEmojiCollection"
title: "Class: RecentEmojiCollection"
sidebar_label: "RecentEmojiCollection"
custom_edit_url: null
---

[whatsapp](../namespaces/whatsapp.md).RecentEmojiCollection

**`whatsapp`** 92671

## Hierarchy

- [`Collection`](whatsapp.Collection.md)<[`RecentEmojiModel`](whatsapp.RecentEmojiModel.md)\>

  ↳ **`RecentEmojiCollection`**

## Constructors

### constructor

• **new RecentEmojiCollection**(`e?`, `t?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `e?` | `any` |
| `t?` | `Object` |
| `t.parent` | `any` |

#### Inherited from

[Collection](whatsapp.Collection.md).[constructor](whatsapp.Collection.md#constructor)

#### Defined in

[packages/wa-js/src/whatsapp/collections/Collection.ts:51](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/collections/Collection.ts#L51)

## Properties

### dirty

• `Optional` **dirty**: `any`

#### Defined in

[packages/wa-js/src/whatsapp/collections/RecentEmojiCollection.ts:25](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/collections/RecentEmojiCollection.ts#L25)

___

### findFirst

• **findFirst**: <S\>(`predicate`: (`this`: `void`, `value`: [`RecentEmojiModel`](whatsapp.RecentEmojiModel.md), `index`: `number`, `obj`: [`RecentEmojiModel`](whatsapp.RecentEmojiModel.md)[]) => value is S, `thisArg?`: `any`) => `undefined` \| `S`(`predicate`: (`value`: [`RecentEmojiModel`](whatsapp.RecentEmojiModel.md), `index`: `number`, `obj`: [`RecentEmojiModel`](whatsapp.RecentEmojiModel.md)[]) => `unknown`, `thisArg?`: `any`) => `undefined` \| [`RecentEmojiModel`](whatsapp.RecentEmojiModel.md)

#### Type declaration

▸ <`S`\>(`predicate`, `thisArg?`): `undefined` \| `S`

Returns the value of the first element in the array where predicate is true, and undefined
otherwise.

##### Type parameters

| Name | Type |
| :------ | :------ |
| `S` | extends [`RecentEmojiModel`](whatsapp.RecentEmojiModel.md)<`S`\> |

##### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `predicate` | (`this`: `void`, `value`: [`RecentEmojiModel`](whatsapp.RecentEmojiModel.md), `index`: `number`, `obj`: [`RecentEmojiModel`](whatsapp.RecentEmojiModel.md)[]) => value is S | find calls predicate once for each element of the array, in ascending order, until it finds one where predicate returns true. If such an element is found, find immediately returns that element value. Otherwise, find returns undefined. |
| `thisArg?` | `any` | If provided, it will be used as the this value for each invocation of predicate. If it is not provided, undefined is used instead. |

##### Returns

`undefined` \| `S`

▸ (`predicate`, `thisArg?`): `undefined` \| [`RecentEmojiModel`](whatsapp.RecentEmojiModel.md)

##### Parameters

| Name | Type |
| :------ | :------ |
| `predicate` | (`value`: [`RecentEmojiModel`](whatsapp.RecentEmojiModel.md), `index`: `number`, `obj`: [`RecentEmojiModel`](whatsapp.RecentEmojiModel.md)[]) => `unknown` |
| `thisArg?` | `any` |

##### Returns

`undefined` \| [`RecentEmojiModel`](whatsapp.RecentEmojiModel.md)

#### Inherited from

[Collection](whatsapp.Collection.md).[findFirst](whatsapp.Collection.md#findfirst)

#### Defined in

[packages/wa-js/src/whatsapp/collections/Collection.ts:87](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/collections/Collection.ts#L87)

___

### modelClass

• **modelClass**: [`RecentEmojiModel`](whatsapp.RecentEmojiModel.md)

#### Inherited from

[Collection](whatsapp.Collection.md).[modelClass](whatsapp.Collection.md#modelclass)

#### Defined in

[packages/wa-js/src/whatsapp/collections/Collection.ts:49](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/collections/Collection.ts#L49)

___

### cachePolicy

▪ `Static` `Optional` **cachePolicy**: `any`

#### Defined in

[packages/wa-js/src/whatsapp/collections/RecentEmojiCollection.ts:23](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/collections/RecentEmojiCollection.ts#L23)

___

### model

▪ `Static` **model**: [`RecentEmojiModel`](whatsapp.RecentEmojiModel.md)

#### Overrides

[Collection](whatsapp.Collection.md).[model](whatsapp.Collection.md#model)

#### Defined in

[packages/wa-js/src/whatsapp/collections/RecentEmojiCollection.ts:24](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/collections/RecentEmojiCollection.ts#L24)

## Accessors

### isCollection

• `get` **isCollection**(): `boolean`

#### Returns

`boolean`

#### Inherited from

Collection.isCollection

#### Defined in

[packages/wa-js/src/whatsapp/collections/Collection.ts:75](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/collections/Collection.ts#L75)

___

### length

• `get` **length**(): `number`

#### Returns

`number`

#### Inherited from

Collection.length

#### Defined in

[packages/wa-js/src/whatsapp/collections/Collection.ts:73](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/collections/Collection.ts#L73)

___

### models

• `get` **models**(): `M`[]

#### Returns

`M`[]

#### Inherited from

Collection.models

#### Defined in

[packages/wa-js/src/whatsapp/collections/Collection.ts:77](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/collections/Collection.ts#L77)

## Methods

### add

▸ **add**(`value`, `options?`): [`RecentEmojiModel`](whatsapp.RecentEmojiModel.md) \| [`RecentEmojiModel`](whatsapp.RecentEmojiModel.md)[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | [`RecentEmojiModel`](whatsapp.RecentEmojiModel.md) \| [`RecentEmojiModel`](whatsapp.RecentEmojiModel.md)[] \| [`WritableProperties`](../namespaces/util.md#writableproperties)<[`RecentEmojiModel`](whatsapp.RecentEmojiModel.md) \| [`RecentEmojiModel`](whatsapp.RecentEmojiModel.md)[]\> |
| `options?` | `Option` |

#### Returns

[`RecentEmojiModel`](whatsapp.RecentEmojiModel.md) \| [`RecentEmojiModel`](whatsapp.RecentEmojiModel.md)[]

#### Inherited from

[Collection](whatsapp.Collection.md).[add](whatsapp.Collection.md#add)

#### Defined in

[packages/wa-js/src/whatsapp/collections/Collection.ts:53](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/collections/Collection.ts#L53)

___

### assertGet

▸ **assertGet**(`e`): [`RecentEmojiModel`](whatsapp.RecentEmojiModel.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `e` | `Stringable` |

#### Returns

[`RecentEmojiModel`](whatsapp.RecentEmojiModel.md)

#### Inherited from

[Collection](whatsapp.Collection.md).[assertGet](whatsapp.Collection.md#assertget)

#### Defined in

[packages/wa-js/src/whatsapp/collections/Collection.ts:69](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/collections/Collection.ts#L69)

___

### at

▸ **at**(`position`): `undefined` \| [`RecentEmojiModel`](whatsapp.RecentEmojiModel.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `position` | `number` |

#### Returns

`undefined` \| [`RecentEmojiModel`](whatsapp.RecentEmojiModel.md)

#### Inherited from

[Collection](whatsapp.Collection.md).[at](whatsapp.Collection.md#at)

#### Defined in

[packages/wa-js/src/whatsapp/collections/Collection.ts:71](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/collections/Collection.ts#L71)

___

### bind

▸ **bind**(`eventName`, `listener`, `context?`): [`RecentEmojiCollection`](whatsapp.RecentEmojiCollection.md)

Alias of `on`

**`alias`** on

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | `Event` |
| `listener` | `Listener` |
| `context?` | `any` |

#### Returns

[`RecentEmojiCollection`](whatsapp.RecentEmojiCollection.md)

#### Inherited from

[Collection](whatsapp.Collection.md).[bind](whatsapp.Collection.md#bind)

#### Defined in

[packages/wa-js/src/whatsapp/misc/EventEmitter.ts:96](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/misc/EventEmitter.ts#L96)

___

### emit

▸ **emit**(`eventName`, ...`args`): [`RecentEmojiCollection`](whatsapp.RecentEmojiCollection.md)

Alias of `trigger`

**`alias`** trigger

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | `Event` |
| `...args` | `any`[] |

#### Returns

[`RecentEmojiCollection`](whatsapp.RecentEmojiCollection.md)

#### Inherited from

[Collection](whatsapp.Collection.md).[emit](whatsapp.Collection.md#emit)

#### Defined in

[packages/wa-js/src/whatsapp/misc/EventEmitter.ts:117](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/misc/EventEmitter.ts#L117)

___

### get

▸ **get**(`e`): `undefined` \| [`RecentEmojiModel`](whatsapp.RecentEmojiModel.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `e` | `Stringable` |

#### Returns

`undefined` \| [`RecentEmojiModel`](whatsapp.RecentEmojiModel.md)

#### Inherited from

[Collection](whatsapp.Collection.md).[get](whatsapp.Collection.md#get)

#### Defined in

[packages/wa-js/src/whatsapp/collections/Collection.ts:67](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/collections/Collection.ts#L67)

___

### getModelsArray

▸ **getModelsArray**(): [`RecentEmojiModel`](whatsapp.RecentEmojiModel.md)[]

#### Returns

[`RecentEmojiModel`](whatsapp.RecentEmojiModel.md)[]

#### Inherited from

[Collection](whatsapp.Collection.md).[getModelsArray](whatsapp.Collection.md#getmodelsarray)

#### Defined in

[packages/wa-js/src/whatsapp/collections/Collection.ts:97](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/collections/Collection.ts#L97)

___

### head

▸ **head**(): `undefined` \| [`RecentEmojiModel`](whatsapp.RecentEmojiModel.md)

#### Returns

`undefined` \| [`RecentEmojiModel`](whatsapp.RecentEmojiModel.md)

#### Inherited from

[Collection](whatsapp.Collection.md).[head](whatsapp.Collection.md#head)

#### Defined in

[packages/wa-js/src/whatsapp/collections/Collection.ts:91](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/collections/Collection.ts#L91)

___

### includes

▸ **includes**(`model`, `position?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `model` | [`RecentEmojiModel`](whatsapp.RecentEmojiModel.md) |
| `position?` | `number` |

#### Returns

`boolean`

#### Inherited from

[Collection](whatsapp.Collection.md).[includes](whatsapp.Collection.md#includes)

#### Defined in

[packages/wa-js/src/whatsapp/collections/Collection.ts:85](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/collections/Collection.ts#L85)

___

### increment

▸ **increment**(`e?`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `e?` | `any` |

#### Returns

`any`

#### Defined in

[packages/wa-js/src/whatsapp/collections/RecentEmojiCollection.ts:28](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/collections/RecentEmojiCollection.ts#L28)

___

### isListening

▸ **isListening**(`eventName`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | `Event` |

#### Returns

`boolean`

#### Inherited from

[Collection](whatsapp.Collection.md).[isListening](whatsapp.Collection.md#islistening)

#### Defined in

[packages/wa-js/src/whatsapp/misc/EventEmitter.ts:90](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/misc/EventEmitter.ts#L90)

___

### isModel

▸ **isModel**(`model`): model is RecentEmojiModel

#### Parameters

| Name | Type |
| :------ | :------ |
| `model` | `any` |

#### Returns

model is RecentEmojiModel

#### Inherited from

[Collection](whatsapp.Collection.md).[isModel](whatsapp.Collection.md#ismodel)

#### Defined in

[packages/wa-js/src/whatsapp/collections/Collection.ts:83](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/collections/Collection.ts#L83)

___

### last

▸ **last**(): `undefined` \| [`RecentEmojiModel`](whatsapp.RecentEmojiModel.md)

#### Returns

`undefined` \| [`RecentEmojiModel`](whatsapp.RecentEmojiModel.md)

#### Inherited from

[Collection](whatsapp.Collection.md).[last](whatsapp.Collection.md#last)

#### Defined in

[packages/wa-js/src/whatsapp/collections/Collection.ts:93](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/collections/Collection.ts#L93)

___

### listenTo

▸ **listenTo**(`context`, `eventName`, `listener?`): [`RecentEmojiCollection`](whatsapp.RecentEmojiCollection.md)

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `context` | `any` | The value of `this` provided for the call to `listener` |
| `eventName` | `Event` | The name of the event. |
| `listener?` | `Listener` | The callback function. |

#### Returns

[`RecentEmojiCollection`](whatsapp.RecentEmojiCollection.md)

#### Inherited from

[Collection](whatsapp.Collection.md).[listenTo](whatsapp.Collection.md#listento)

#### Defined in

[packages/wa-js/src/whatsapp/misc/EventEmitter.ts:74](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/misc/EventEmitter.ts#L74)

___

### listenToAndRun

▸ **listenToAndRun**(`context`, `eventName`, `listener?`): [`RecentEmojiCollection`](whatsapp.RecentEmojiCollection.md)

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `context` | `any` | The value of `this` provided for the call to `listener` |
| `eventName` | `Event` | The name of the event. |
| `listener?` | `Listener` | The callback function. |

#### Returns

[`RecentEmojiCollection`](whatsapp.RecentEmojiCollection.md)

#### Inherited from

[Collection](whatsapp.Collection.md).[listenToAndRun](whatsapp.Collection.md#listentoandrun)

#### Defined in

[packages/wa-js/src/whatsapp/misc/EventEmitter.ts:88](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/misc/EventEmitter.ts#L88)

___

### listenToOnce

▸ **listenToOnce**(`context`, `eventName`, `listener?`): [`RecentEmojiCollection`](whatsapp.RecentEmojiCollection.md)

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `context` | `any` | The value of `this` provided for the call to `listener` |
| `eventName` | `Event` | The name of the event. |
| `listener?` | `Listener` | The callback function. |

#### Returns

[`RecentEmojiCollection`](whatsapp.RecentEmojiCollection.md)

#### Inherited from

[Collection](whatsapp.Collection.md).[listenToOnce](whatsapp.Collection.md#listentoonce)

#### Defined in

[packages/wa-js/src/whatsapp/misc/EventEmitter.ts:81](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/misc/EventEmitter.ts#L81)

___

### off

▸ **off**(`eventName?`, `listener?`, `context?`): [`RecentEmojiCollection`](whatsapp.RecentEmojiCollection.md)

Removes the specified listener from the listener array for the event named eventName.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `eventName?` | `Event` | The name of the event. |
| `listener?` | `Listener` | The callback function. |
| `context?` | `any` | The value of `this` provided for the call to `listener` |

#### Returns

[`RecentEmojiCollection`](whatsapp.RecentEmojiCollection.md)

Returns a reference to the `EventEmitter`, so that calls can be chained.

#### Inherited from

[Collection](whatsapp.Collection.md).[off](whatsapp.Collection.md#off)

#### Defined in

[packages/wa-js/src/whatsapp/misc/EventEmitter.ts:59](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/misc/EventEmitter.ts#L59)

___

### on

▸ **on**(`eventName`, `listener`, `context?`): [`RecentEmojiCollection`](whatsapp.RecentEmojiCollection.md)

Adds the listener function to the end of the listeners array for the event named eventName.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `eventName` | `Event` | The name of the event. |
| `listener` | `Listener` | The callback function. |
| `context?` | `any` | The value of `this` provided for the call to `listener` |

#### Returns

[`RecentEmojiCollection`](whatsapp.RecentEmojiCollection.md)

Returns a reference to the `EventEmitter`, so that calls can be chained.

#### Inherited from

[Collection](whatsapp.Collection.md).[on](whatsapp.Collection.md#on)

#### Defined in

[packages/wa-js/src/whatsapp/misc/EventEmitter.ts:39](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/misc/EventEmitter.ts#L39)

___

### once

▸ **once**(`eventName`, `listener`, `context?`): [`RecentEmojiCollection`](whatsapp.RecentEmojiCollection.md)

Adds a one-time listener function for the event named eventName.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `eventName` | `Event` | The name of the event. |
| `listener` | `Listener` | The callback function. |
| `context?` | `any` | The value of `this` provided for the call to `listener` |

#### Returns

[`RecentEmojiCollection`](whatsapp.RecentEmojiCollection.md)

Returns a reference to the `EventEmitter`, so that calls can be chained.

#### Inherited from

[Collection](whatsapp.Collection.md).[once](whatsapp.Collection.md#once)

#### Defined in

[packages/wa-js/src/whatsapp/misc/EventEmitter.ts:49](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/misc/EventEmitter.ts#L49)

___

### remove

▸ **remove**(`value`, `options?`): [`RecentEmojiModel`](whatsapp.RecentEmojiModel.md)[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | [`RecentEmojiModel`](whatsapp.RecentEmojiModel.md) \| [`RecentEmojiModel`](whatsapp.RecentEmojiModel.md)[] |
| `options?` | `Object` |
| `options.index?` | `boolean` |
| `options.silent?` | `boolean` |

#### Returns

[`RecentEmojiModel`](whatsapp.RecentEmojiModel.md)[]

#### Inherited from

[Collection](whatsapp.Collection.md).[remove](whatsapp.Collection.md#remove)

#### Defined in

[packages/wa-js/src/whatsapp/collections/Collection.ts:57](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/collections/Collection.ts#L57)

___

### removeAllListeners

▸ **removeAllListeners**(): [`RecentEmojiCollection`](whatsapp.RecentEmojiCollection.md)

Removes all listeners.

#### Returns

[`RecentEmojiCollection`](whatsapp.RecentEmojiCollection.md)

Returns a reference to the `EventEmitter`, so that calls can be chained.

#### Inherited from

[Collection](whatsapp.Collection.md).[removeAllListeners](whatsapp.Collection.md#removealllisteners)

#### Defined in

[packages/wa-js/src/whatsapp/misc/EventEmitter.ts:112](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/misc/EventEmitter.ts#L112)

___

### removeListener

▸ **removeListener**(`eventName?`, `listener?`, `context?`): [`RecentEmojiCollection`](whatsapp.RecentEmojiCollection.md)

Alias of `off`

**`alias`** off

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName?` | `Event` |
| `listener?` | `Listener` |
| `context?` | `any` |

#### Returns

[`RecentEmojiCollection`](whatsapp.RecentEmojiCollection.md)

#### Inherited from

[Collection](whatsapp.Collection.md).[removeListener](whatsapp.Collection.md#removelistener)

#### Defined in

[packages/wa-js/src/whatsapp/misc/EventEmitter.ts:107](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/misc/EventEmitter.ts#L107)

___

### reorder

▸ **reorder**(`e`, `t`): [`RecentEmojiModel`](whatsapp.RecentEmojiModel.md)[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `e` | `number` |
| `t` | `number` |

#### Returns

[`RecentEmojiModel`](whatsapp.RecentEmojiModel.md)[]

#### Inherited from

[Collection](whatsapp.Collection.md).[reorder](whatsapp.Collection.md#reorder)

#### Defined in

[packages/wa-js/src/whatsapp/collections/Collection.ts:99](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/collections/Collection.ts#L99)

___

### reorderMutate

▸ **reorderMutate**(`e`, `t`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `e` | `any` |
| `t` | `any` |

#### Returns

`void`

#### Inherited from

[Collection](whatsapp.Collection.md).[reorderMutate](whatsapp.Collection.md#reordermutate)

#### Defined in

[packages/wa-js/src/whatsapp/collections/Collection.ts:65](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/collections/Collection.ts#L65)

___

### replaceId

▸ **replaceId**(`e`, `t`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `e` | `any` |
| `t` | `any` |

#### Returns

`void`

#### Inherited from

[Collection](whatsapp.Collection.md).[replaceId](whatsapp.Collection.md#replaceid)

#### Defined in

[packages/wa-js/src/whatsapp/collections/Collection.ts:63](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/collections/Collection.ts#L63)

___

### reset

▸ **reset**(): `void`

#### Returns

`void`

#### Inherited from

[Collection](whatsapp.Collection.md).[reset](whatsapp.Collection.md#reset)

#### Defined in

[packages/wa-js/src/whatsapp/collections/Collection.ts:59](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/collections/Collection.ts#L59)

___

### serialize

▸ **serialize**(): `any`[]

#### Returns

`any`[]

#### Inherited from

[Collection](whatsapp.Collection.md).[serialize](whatsapp.Collection.md#serialize)

#### Defined in

[packages/wa-js/src/whatsapp/collections/Collection.ts:79](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/collections/Collection.ts#L79)

___

### set

▸ **set**(`value`, `options?`): [`RecentEmojiModel`](whatsapp.RecentEmojiModel.md) \| [`RecentEmojiModel`](whatsapp.RecentEmojiModel.md)[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | [`RecentEmojiModel`](whatsapp.RecentEmojiModel.md) \| [`RecentEmojiModel`](whatsapp.RecentEmojiModel.md)[] |
| `options?` | `Option` |

#### Returns

[`RecentEmojiModel`](whatsapp.RecentEmojiModel.md) \| [`RecentEmojiModel`](whatsapp.RecentEmojiModel.md)[]

#### Inherited from

[Collection](whatsapp.Collection.md).[set](whatsapp.Collection.md#set)

#### Defined in

[packages/wa-js/src/whatsapp/collections/Collection.ts:55](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/collections/Collection.ts#L55)

___

### sort

▸ **sort**(`options?`): [`RecentEmojiCollection`](whatsapp.RecentEmojiCollection.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | `Object` |
| `options.silent?` | `boolean` |

#### Returns

[`RecentEmojiCollection`](whatsapp.RecentEmojiCollection.md)

#### Inherited from

[Collection](whatsapp.Collection.md).[sort](whatsapp.Collection.md#sort)

#### Defined in

[packages/wa-js/src/whatsapp/collections/Collection.ts:61](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/collections/Collection.ts#L61)

___

### stopListening

▸ **stopListening**(`context?`, `eventName?`, `listener?`): [`RecentEmojiCollection`](whatsapp.RecentEmojiCollection.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `context?` | `any` |
| `eventName?` | `Event` |
| `listener?` | `Listener` |

#### Returns

[`RecentEmojiCollection`](whatsapp.RecentEmojiCollection.md)

#### Inherited from

[Collection](whatsapp.Collection.md).[stopListening](whatsapp.Collection.md#stoplistening)

#### Defined in

[packages/wa-js/src/whatsapp/misc/EventEmitter.ts:67](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/misc/EventEmitter.ts#L67)

___

### sync

▸ **sync**(): `any`

#### Returns

`any`

#### Defined in

[packages/wa-js/src/whatsapp/collections/RecentEmojiCollection.ts:26](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/collections/RecentEmojiCollection.ts#L26)

___

### throttledSync

▸ **throttledSync**(): `any`

#### Returns

`any`

#### Defined in

[packages/wa-js/src/whatsapp/collections/RecentEmojiCollection.ts:27](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/collections/RecentEmojiCollection.ts#L27)

___

### toArray

▸ **toArray**(): [`RecentEmojiModel`](whatsapp.RecentEmojiModel.md)[]

#### Returns

[`RecentEmojiModel`](whatsapp.RecentEmojiModel.md)[]

#### Inherited from

[Collection](whatsapp.Collection.md).[toArray](whatsapp.Collection.md#toarray)

#### Defined in

[packages/wa-js/src/whatsapp/collections/Collection.ts:95](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/collections/Collection.ts#L95)

___

### toJSON

▸ **toJSON**(): `any`[]

#### Returns

`any`[]

#### Inherited from

[Collection](whatsapp.Collection.md).[toJSON](whatsapp.Collection.md#tojson)

#### Defined in

[packages/wa-js/src/whatsapp/collections/Collection.ts:81](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/collections/Collection.ts#L81)

___

### trigger

▸ **trigger**(`eventName`, ...`args`): [`RecentEmojiCollection`](whatsapp.RecentEmojiCollection.md)

Synchronously calls each of the listeners registered for the event named eventName, in the order they were registered, passing the supplied arguments to each.

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | `Event` |
| `...args` | `any`[] |

#### Returns

[`RecentEmojiCollection`](whatsapp.RecentEmojiCollection.md)

Returns a reference to the `EventEmitter`, so that calls can be chained.

#### Inherited from

[Collection](whatsapp.Collection.md).[trigger](whatsapp.Collection.md#trigger)

#### Defined in

[packages/wa-js/src/whatsapp/misc/EventEmitter.ts:65](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/misc/EventEmitter.ts#L65)

___

### unbind

▸ **unbind**(`eventName?`, `listener?`, `context?`): [`RecentEmojiCollection`](whatsapp.RecentEmojiCollection.md)

Alias of `off`

**`alias`** off

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName?` | `Event` |
| `listener?` | `Listener` |
| `context?` | `any` |

#### Returns

[`RecentEmojiCollection`](whatsapp.RecentEmojiCollection.md)

#### Inherited from

[Collection](whatsapp.Collection.md).[unbind](whatsapp.Collection.md#unbind)

#### Defined in

[packages/wa-js/src/whatsapp/misc/EventEmitter.ts:102](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/misc/EventEmitter.ts#L102)

___

### where

▸ **where**(`ids`): [`RecentEmojiModel`](whatsapp.RecentEmojiModel.md)[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `ids` | `Stringable`[] |

#### Returns

[`RecentEmojiModel`](whatsapp.RecentEmojiModel.md)[]

#### Inherited from

[Collection](whatsapp.Collection.md).[where](whatsapp.Collection.md#where)

#### Defined in

[packages/wa-js/src/whatsapp/collections/Collection.ts:89](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/collections/Collection.ts#L89)

___

### comparator

▸ `Static` **comparator**(): `any`

#### Returns

`any`

#### Overrides

Collection.comparator

#### Defined in

[packages/wa-js/src/whatsapp/collections/RecentEmojiCollection.ts:29](https://github.com/wppconnect-team/wa-js/blob/main/src/whatsapp/collections/RecentEmojiCollection.ts#L29)