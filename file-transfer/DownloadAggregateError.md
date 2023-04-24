# Class DownloadAggregateError

## 🏭 Constructors

### constructor

```ts
new DownloadAggregateError(message: string, urls: string[], headers: Record<string, any>, destination: string, errors: Object): DownloadAggregateError
```
#### Parameters

- **message**: `string`
- **urls**: `string[]`
- **headers**: `Record<string, any>`
- **destination**: `string`
- **errors**: `Object`
#### Return Type

- `DownloadAggregateError`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/file-transfer/error.ts#L52" target="_blank" rel="noreferrer">packages/file-transfer/error.ts:52</a>
</p>


## 🏷️ Properties

### destination <Badge type="tip" text="readonly" />

```ts
destination: string
```
*Inherited from: DownloadError.destination*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/file-transfer/error.ts#L8" target="_blank" rel="noreferrer">packages/file-transfer/error.ts:8</a>
</p>


### errors <Badge type="tip" text="readonly" />

```ts
errors: Object
```
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/file-transfer/error.ts#L57" target="_blank" rel="noreferrer">packages/file-transfer/error.ts:57</a>
</p>


### headers <Badge type="tip" text="readonly" />

```ts
headers: Record<string, any>
```
*Inherited from: DownloadError.headers*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/file-transfer/error.ts#L7" target="_blank" rel="noreferrer">packages/file-transfer/error.ts:7</a>
</p>


### urls <Badge type="tip" text="public" />

```ts
urls: string[]
```
*Inherited from: DownloadError.urls*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/file-transfer/error.ts#L6" target="_blank" rel="noreferrer">packages/file-transfer/error.ts:6</a>
</p>


