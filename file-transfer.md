# Download Core

[![npm version](https://img.shields.io/npm/v/@xmcl/file-transfer.svg)](https://www.npmjs.com/package/@xmcl/file-transfer)
[![Downloads](https://img.shields.io/npm/dm/@xmcl/file-transfer.svg)](https://npmjs.com/@xmcl/file-transfer)
[![Install size](https://packagephobia.now.sh/badge?p=@xmcl/file-transfer)](https://packagephobia.now.sh/result?p=@xmcl/file-transfer)
[![npm](https://img.shields.io/npm/l/@xmcl/minecraft-launcher-core.svg)](https://github.com/voxelum/minecraft-launcher-core-node/blob/master/LICENSE)
[![Build Status](https://github.com/voxelum/minecraft-launcher-core-node/workflows/Build/badge.svg)](https://github.com/Voxelum/minecraft-launcher-core-node/actions?query=workflow%3ABuild)

Provide a high performance download file function based on [undici](https://github.com/nodejs/undici).

- Support download by range request
  - Customize the range size
- Support validating the checksum
  - If the validation matched, it won't download the file.
  - Also support customize validation.
- Support download and fallback to another url
- Support AbortSignal
- Fully customizable retry logic

## Usage

Download the file by url

```ts
import { download } from '@xmcl/file-transfer'

await download({
  url: 'http://example.com/file.zip', // required
  destination: 'file.zip', // required
  headers: { // optional
    'customized': 'header'
  },
  abortSignal: new AbortController().signal, // optional
  progressController: (url, chunkSize, progress, total) => { // optional
    console.log(url)
    console.log(chunkSize)
    console.log(progress)
    console.log(total)
  },
  // use validator to validate the file
  validator: { // optional
    algorithm: 'sha1',
    hash: '1234567890abcdef1234567890abcdef12345678',
  }
})
```

Download with fallback url

```ts
import { download } from '@xmcl/file-transfer'

await download({
  // using array to fallback
  url: ['http://example.com/file.zip', 'http://example.com/fallback.zip'],
  destination: 'file.zip',
})
```

## 🧾 Classes

<div class="definition-grid class"><a href="file-transfer/ChecksumNotMatchError">ChecksumNotMatchError</a><a href="file-transfer/ChecksumValidator">ChecksumValidator</a><a href="file-transfer/DefaultRangePolicy">DefaultRangePolicy</a><a href="file-transfer/DownloadAbortError">DownloadAbortError</a><a href="file-transfer/DownloadAgent">DownloadAgent</a><a href="file-transfer/DownloadAggregateError">DownloadAggregateError</a><a href="file-transfer/DownloadError">DownloadError</a><a href="file-transfer/DownloadFileSystemError">DownloadFileSystemError</a><a href="file-transfer/JsonValidator">JsonValidator</a><a href="file-transfer/ValidationError">ValidationError</a></div>

## 🤝 Interfaces

<div class="definition-grid interface"><a href="file-transfer/AbortSignal">AbortSignal</a><a href="file-transfer/ChecksumValidatorOptions">ChecksumValidatorOptions</a><a href="file-transfer/DefaultRangePolicyOptions">DefaultRangePolicyOptions</a><a href="file-transfer/DownloadAgentOptions">DownloadAgentOptions</a><a href="file-transfer/DownloadBaseOptions">DownloadBaseOptions</a><a href="file-transfer/DownloadOptions">DownloadOptions</a><a href="file-transfer/ProgressController">ProgressController</a><a href="file-transfer/Range">Range</a><a href="file-transfer/RangePolicy">RangePolicy</a><a href="file-transfer/Validator">Validator</a></div>

## 🏭 Functions

### createProgressController

```ts
createProgressController(onProgress: Function): ProgressController
```
#### Parameters

- **onProgress**: `Function`
#### Return Type

- `ProgressController`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/file-transfer/progress.ts#L11" target="_blank" rel="noreferrer">packages/file-transfer/progress.ts:11</a>
</p>


### download

```ts
download(options: DownloadOptions): Promise<void>
```
Download url or urls to a file path. This process is abortable, it's compatible with the dom like ``AbortSignal``.
#### Parameters

- **options**: `DownloadOptions`
#### Return Type

- `Promise<void>`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/file-transfer/download.ts#L63" target="_blank" rel="noreferrer">packages/file-transfer/download.ts:63</a>
</p>


### isRangePolicy

```ts
isRangePolicy(rangeOptions: RangePolicy | DefaultRangePolicyOptions): rangeOptions is RangePolicy
```
#### Parameters

- **rangeOptions**: `RangePolicy | DefaultRangePolicyOptions`
#### Return Type

- `rangeOptions is RangePolicy`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/file-transfer/rangePolicy.ts#L10" target="_blank" rel="noreferrer">packages/file-transfer/rangePolicy.ts:10</a>
</p>


### isValidator

```ts
isValidator(options: Validator | ChecksumValidatorOptions): options is Validator
```
#### Parameters

- **options**: `Validator | ChecksumValidatorOptions`
#### Return Type

- `options is Validator`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/file-transfer/validator.ts#L33" target="_blank" rel="noreferrer">packages/file-transfer/validator.ts:33</a>
</p>


### resolveAbortSignal

```ts
resolveAbortSignal(signal: AbortSignal): AbortSignal
```
#### Parameters

- **signal**: `AbortSignal`
#### Return Type

- `AbortSignal`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/file-transfer/abort.ts#L1" target="_blank" rel="noreferrer">packages/file-transfer/abort.ts:1</a>
</p>


### resolveAgent

```ts
resolveAgent(agent: DownloadAgentOptions | DownloadAgent): DownloadAgent
```
#### Parameters

- **agent**: `DownloadAgentOptions | DownloadAgent`
#### Return Type

- `DownloadAgent`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/file-transfer/agent.ts#L21" target="_blank" rel="noreferrer">packages/file-transfer/agent.ts:21</a>
</p>


### resolveProgressController

```ts
resolveProgressController(controller: ProgressController | Function): ProgressController
```
#### Parameters

- **controller**: `ProgressController | Function`
#### Return Type

- `ProgressController`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/file-transfer/progress.ts#L23" target="_blank" rel="noreferrer">packages/file-transfer/progress.ts:23</a>
</p>


### resolveRangePolicy

```ts
resolveRangePolicy(rangeOptions: RangePolicy | DefaultRangePolicyOptions): RangePolicy
```
#### Parameters

- **rangeOptions**: `RangePolicy | DefaultRangePolicyOptions`
#### Return Type

- `RangePolicy`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/file-transfer/rangePolicy.ts#L15" target="_blank" rel="noreferrer">packages/file-transfer/rangePolicy.ts:15</a>
</p>


### resolveValidator

```ts
resolveValidator(options: Validator | ChecksumValidatorOptions): Validator
```
#### Parameters

- **options**: `Validator | ChecksumValidatorOptions`
#### Return Type

- `Validator`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/file-transfer/validator.ts#L38" target="_blank" rel="noreferrer">packages/file-transfer/validator.ts:38</a>
</p>



