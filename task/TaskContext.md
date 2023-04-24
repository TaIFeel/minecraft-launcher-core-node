# Interface TaskContext

## 🔧 Methods

### fork <Badge type="info" text="optional" />

```ts
fork(task: Task<any>): number
```
#### Parameters

- **task**: `Task<any>`
#### Return Type

- `number`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L67" target="_blank" rel="noreferrer">packages/task/index.ts:67</a>
</p>


### onCancelled <Badge type="info" text="optional" />

```ts
onCancelled(task: Task<any>): void
```
#### Parameters

- **task**: `Task<any>`
#### Return Type

- `void`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L74" target="_blank" rel="noreferrer">packages/task/index.ts:74</a>
</p>


### onFailed <Badge type="info" text="optional" />

```ts
onFailed(task: Task<any>, error: any): void
```
#### Parameters

- **task**: `Task<any>`
- **error**: `any`
#### Return Type

- `void`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L70" target="_blank" rel="noreferrer">packages/task/index.ts:70</a>
</p>


### onPaused <Badge type="info" text="optional" />

```ts
onPaused(task: Task<any>): void
```
#### Parameters

- **task**: `Task<any>`
#### Return Type

- `void`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L72" target="_blank" rel="noreferrer">packages/task/index.ts:72</a>
</p>


### onResumed <Badge type="info" text="optional" />

```ts
onResumed(task: Task<any>): void
```
#### Parameters

- **task**: `Task<any>`
#### Return Type

- `void`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L73" target="_blank" rel="noreferrer">packages/task/index.ts:73</a>
</p>


### onStart <Badge type="info" text="optional" />

```ts
onStart(task: Task<any>): void
```
#### Parameters

- **task**: `Task<any>`
#### Return Type

- `void`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L68" target="_blank" rel="noreferrer">packages/task/index.ts:68</a>
</p>


### onSucceed <Badge type="info" text="optional" />

```ts
onSucceed(task: Task<any>, result: any): void
```
#### Parameters

- **task**: `Task<any>`
- **result**: `any`
#### Return Type

- `void`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L71" target="_blank" rel="noreferrer">packages/task/index.ts:71</a>
</p>


### onUpdate <Badge type="info" text="optional" />

```ts
onUpdate(task: Task<any>, chunkSize: number): void
```
#### Parameters

- **task**: `Task<any>`
- **chunkSize**: `number`
#### Return Type

- `void`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L69" target="_blank" rel="noreferrer">packages/task/index.ts:69</a>
</p>


