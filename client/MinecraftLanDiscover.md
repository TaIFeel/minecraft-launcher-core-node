# Class MinecraftLanDiscover

## 🏭 Constructors

### constructor

```ts
new MinecraftLanDiscover(): MinecraftLanDiscover
```
#### Return Type

- `MinecraftLanDiscover`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/client/lan.ts#L23" target="_blank" rel="noreferrer">packages/client/lan.ts:23</a>
</p>


## 🏷️ Properties

### #ready <Badge type="danger" text="private" />

```ts
#ready: boolean = false
```
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/client/lan.ts#L17" target="_blank" rel="noreferrer">packages/client/lan.ts:17</a>
</p>


### socket <Badge type="tip" text="readonly" />

```ts
socket: Socket
```
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/client/lan.ts#L15" target="_blank" rel="noreferrer">packages/client/lan.ts:15</a>
</p>


## 🔑 Accessors

### isReady

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/client/lan.ts#L19" target="_blank" rel="noreferrer">packages/client/lan.ts:19</a>
</p>


## 🔧 Methods

### addListener

```ts
addListener(channel: "discover", listener: Function): MinecraftLanDiscover
```
#### Parameters

- **channel**: `"discover"`
- **listener**: `Function`
#### Return Type

- `MinecraftLanDiscover`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/client/lan.ts#L10" target="_blank" rel="noreferrer">packages/client/lan.ts:10</a>
</p>


### bind

```ts
bind(): Promise<void>
```
#### Return Type

- `Promise<void>`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/client/lan.ts#L63" target="_blank" rel="noreferrer">packages/client/lan.ts:63</a>
</p>


### broadcast

```ts
broadcast(inf: LanServerInfo): Promise<number>
```
#### Parameters

- **inf**: `LanServerInfo`
#### Return Type

- `Promise<number>`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/client/lan.ts#L54" target="_blank" rel="noreferrer">packages/client/lan.ts:54</a>
</p>


### destroy

```ts
destroy(): Promise<void>
```
#### Return Type

- `Promise<void>`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/client/lan.ts#L73" target="_blank" rel="noreferrer">packages/client/lan.ts:73</a>
</p>


### on

```ts
on(channel: "discover", listener: Function): MinecraftLanDiscover
```
#### Parameters

- **channel**: `"discover"`
- **listener**: `Function`
#### Return Type

- `MinecraftLanDiscover`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/client/lan.ts#L8" target="_blank" rel="noreferrer">packages/client/lan.ts:8</a>
</p>


### once

```ts
once(channel: "discover", listener: Function): MinecraftLanDiscover
```
#### Parameters

- **channel**: `"discover"`
- **listener**: `Function`
#### Return Type

- `MinecraftLanDiscover`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/client/lan.ts#L9" target="_blank" rel="noreferrer">packages/client/lan.ts:9</a>
</p>


### removeListener

```ts
removeListener(channel: "discover", listener: Function): MinecraftLanDiscover
```
#### Parameters

- **channel**: `"discover"`
- **listener**: `Function`
#### Return Type

- `MinecraftLanDiscover`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/client/lan.ts#L11" target="_blank" rel="noreferrer">packages/client/lan.ts:11</a>
</p>


