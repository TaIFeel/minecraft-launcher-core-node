# Class DownloadFileSystemError

## 🏭 Constructors

### constructor

```ts
new DownloadFileSystemError(message: string, urls: string[], headers: Record<string, any>, destination: string, error: unknown): DownloadFileSystemError
```
#### Parameters

- **message**: `string`
- **urls**: `string[]`
- **headers**: `Record<string, any>`
- **destination**: `string`
- **error**: `unknown`
#### Return Type

- `DownloadFileSystemError`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/file-transfer/error.ts#L34" target="_blank" rel="noreferrer">packages/file-transfer/error.ts:34</a>
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


### error <Badge type="tip" text="readonly" />

```ts
error: unknown
```
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/file-transfer/error.ts#L39" target="_blank" rel="noreferrer">packages/file-transfer/error.ts:39</a>
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


