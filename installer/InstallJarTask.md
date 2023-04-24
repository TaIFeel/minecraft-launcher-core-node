# Class InstallJarTask

The controller that maintain the download status
## 🏭 Constructors

### constructor

```ts
new InstallJarTask(version: ResolvedVersion & Object, minecraft: MinecraftLocation, options: Options): InstallJarTask
```
#### Parameters

- **version**: `ResolvedVersion & Object`
- **minecraft**: `MinecraftLocation`
- **options**: `Options`
#### Return Type

- `InstallJarTask`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/installer/minecraft.ts#L419" target="_blank" rel="noreferrer">packages/installer/minecraft.ts:419</a>
</p>


## 🏷️ Properties

### _from <Badge type="warning" text="protected" />

```ts
_from: undefined | string
```
*Inherited from: DownloadTask._from*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L89" target="_blank" rel="noreferrer">packages/task/index.ts:89</a>
</p>


### _id <Badge type="warning" text="protected" />

```ts
_id: number = 0
```
*Inherited from: DownloadTask._id*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L94" target="_blank" rel="noreferrer">packages/task/index.ts:94</a>
</p>


### _path <Badge type="warning" text="protected" />

```ts
_path: string = ''
```
*Inherited from: DownloadTask._path*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L93" target="_blank" rel="noreferrer">packages/task/index.ts:93</a>
</p>


### _pausing <Badge type="warning" text="protected" />

```ts
_pausing: Promise<void> = ...
```
*Inherited from: DownloadTask._pausing*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L227" target="_blank" rel="noreferrer">packages/task/index.ts:227</a>
</p>


### _progress <Badge type="warning" text="protected" />

```ts
_progress: number = 0
```
*Inherited from: DownloadTask._progress*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L91" target="_blank" rel="noreferrer">packages/task/index.ts:91</a>
</p>


### _promise <Badge type="warning" text="protected" />

```ts
_promise: Promise<void>
```
*Inherited from: DownloadTask._promise*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L84" target="_blank" rel="noreferrer">packages/task/index.ts:84</a>
</p>


### _state <Badge type="warning" text="protected" />

```ts
_state: TaskState = TaskState.Idle
```
*Inherited from: DownloadTask._state*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L83" target="_blank" rel="noreferrer">packages/task/index.ts:83</a>
</p>


### _to <Badge type="warning" text="protected" />

```ts
_to: undefined | string
```
*Inherited from: DownloadTask._to*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L90" target="_blank" rel="noreferrer">packages/task/index.ts:90</a>
</p>


### _total <Badge type="warning" text="protected" />

```ts
_total: number = -1
```
*Inherited from: DownloadTask._total*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L92" target="_blank" rel="noreferrer">packages/task/index.ts:92</a>
</p>


### abort <Badge type="warning" text="protected" />

```ts
abort: Function = ...
```
*Inherited from: DownloadTask.abort*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/installer/downloadTask.ts#L5" target="_blank" rel="noreferrer">packages/installer/downloadTask.ts:5</a>
</p>


### context

```ts
context: TaskContext = {}
```
*Inherited from: DownloadTask.context*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L97" target="_blank" rel="noreferrer">packages/task/index.ts:97</a>
</p>


### name

```ts
name: string = ''
```
*Inherited from: DownloadTask.name*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L99" target="_blank" rel="noreferrer">packages/task/index.ts:99</a>
</p>


### options <Badge type="warning" text="protected" />

```ts
options: DownloadOptions
```
*Inherited from: DownloadTask.options*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/installer/downloadTask.ts#L7" target="_blank" rel="noreferrer">packages/installer/downloadTask.ts:7</a>
</p>


### param

```ts
param: object = {}
```
*Inherited from: DownloadTask.param*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L100" target="_blank" rel="noreferrer">packages/task/index.ts:100</a>
</p>


### parent

```ts
parent: undefined | Task<any>
```
*Inherited from: DownloadTask.parent*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L96" target="_blank" rel="noreferrer">packages/task/index.ts:96</a>
</p>


### reject <Badge type="warning" text="protected" />

```ts
reject: Function
```
*Inherited from: DownloadTask.reject*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L87" target="_blank" rel="noreferrer">packages/task/index.ts:87</a>
</p>


### resolve <Badge type="warning" text="protected" />

```ts
resolve: Function
```
*Inherited from: DownloadTask.resolve*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L86" target="_blank" rel="noreferrer">packages/task/index.ts:86</a>
</p>


### resultOrError <Badge type="warning" text="protected" />

```ts
resultOrError: any
```
*Inherited from: DownloadTask.resultOrError*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L102" target="_blank" rel="noreferrer">packages/task/index.ts:102</a>
</p>


## 🔑 Accessors

### from

*Inherited from: DownloadTask.from*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L130" target="_blank" rel="noreferrer">packages/task/index.ts:130</a>
</p>


### id

*Inherited from: DownloadTask.id*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L125" target="_blank" rel="noreferrer">packages/task/index.ts:125</a>
</p>


### isCancelled

*Inherited from: DownloadTask.isCancelled*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L133" target="_blank" rel="noreferrer">packages/task/index.ts:133</a>
</p>


### isDone

*Inherited from: DownloadTask.isDone*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L135" target="_blank" rel="noreferrer">packages/task/index.ts:135</a>
</p>


### isPaused

*Inherited from: DownloadTask.isPaused*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L134" target="_blank" rel="noreferrer">packages/task/index.ts:134</a>
</p>


### isRunning

*Inherited from: DownloadTask.isRunning*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L136" target="_blank" rel="noreferrer">packages/task/index.ts:136</a>
</p>


### path

*Inherited from: DownloadTask.path*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L126" target="_blank" rel="noreferrer">packages/task/index.ts:126</a>
</p>


### progress

*Inherited from: DownloadTask.progress*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L127" target="_blank" rel="noreferrer">packages/task/index.ts:127</a>
</p>


### state

*Inherited from: DownloadTask.state*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L131" target="_blank" rel="noreferrer">packages/task/index.ts:131</a>
</p>


### to

*Inherited from: DownloadTask.to*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L129" target="_blank" rel="noreferrer">packages/task/index.ts:129</a>
</p>


### total

*Inherited from: DownloadTask.total*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L128" target="_blank" rel="noreferrer">packages/task/index.ts:128</a>
</p>


## 🔧 Methods

### _onAborted <Badge type="warning" text="protected" />

```ts
_onAborted(): void
```
#### Return Type

- `void`

*Inherited from: DownloadTask._onAborted*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L229" target="_blank" rel="noreferrer">packages/task/index.ts:229</a>
</p>


### _onResume <Badge type="warning" text="protected" />

```ts
_onResume(): void
```
#### Return Type

- `void`

*Inherited from: DownloadTask._onResume*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L230" target="_blank" rel="noreferrer">packages/task/index.ts:230</a>
</p>


### _unpause <Badge type="warning" text="protected" />

```ts
_unpause(): void
```
#### Return Type

- `void`

*Inherited from: DownloadTask._unpause*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L228" target="_blank" rel="noreferrer">packages/task/index.ts:228</a>
</p>


### cancel

```ts
cancel(): Promise<void>
```
#### Return Type

- `Promise<void>`

*Inherited from: DownloadTask.cancel*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L154" target="_blank" rel="noreferrer">packages/task/index.ts:154</a>
</p>


### cancelTask <Badge type="warning" text="protected" />

```ts
cancelTask(): Promise<void>
```
#### Return Type

- `Promise<void>`

*Inherited from: DownloadTask.cancelTask*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L236" target="_blank" rel="noreferrer">packages/task/index.ts:236</a>
</p>


### get

```ts
get(): void
```
#### Return Type

- `void`

*Inherited from: DownloadTask.get*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L117" target="_blank" rel="noreferrer">packages/task/index.ts:117</a>
</p>


### isAbortedError <Badge type="warning" text="protected" />

```ts
isAbortedError(e: any): boolean
```
#### Parameters

- **e**: `any`
#### Return Type

- `boolean`

*Inherited from: DownloadTask.isAbortedError*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/installer/downloadTask.ts#L47" target="_blank" rel="noreferrer">packages/installer/downloadTask.ts:47</a>
</p>


### map

```ts
map(transform: Transform<InstallJarTask, N>): Task<N>
```
#### Parameters

- **transform**: `Transform<InstallJarTask, N>`
#### Return Type

- `Task<N>`

*Inherited from: DownloadTask.map*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L215" target="_blank" rel="noreferrer">packages/task/index.ts:215</a>
</p>


### onChildUpdate

```ts
onChildUpdate(chunkSize: number): void
```
#### Parameters

- **chunkSize**: `number`
#### Return Type

- `void`

*Inherited from: DownloadTask.onChildUpdate*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L208" target="_blank" rel="noreferrer">packages/task/index.ts:208</a>
</p>


### onProgress

```ts
onProgress(url: URL, chunkSize: number, progress: number, total: number): void
```
#### Parameters

- **url**: `URL`
- **chunkSize**: `number`
- **progress**: `number`
- **total**: `number`
#### Return Type

- `void`

*Inherited from: DownloadTask.onProgress*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/installer/downloadTask.ts#L13" target="_blank" rel="noreferrer">packages/installer/downloadTask.ts:13</a>
</p>


### pause

```ts
pause(): Promise<void>
```
#### Return Type

- `Promise<void>`

*Inherited from: DownloadTask.pause*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L138" target="_blank" rel="noreferrer">packages/task/index.ts:138</a>
</p>


### pauseTask <Badge type="warning" text="protected" />

```ts
pauseTask(): Promise<void>
```
#### Return Type

- `Promise<void>`

*Inherited from: DownloadTask.pauseTask*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L243" target="_blank" rel="noreferrer">packages/task/index.ts:243</a>
</p>


### process <Badge type="warning" text="protected" />

```ts
process(): Promise<void>
```
#### Return Type

- `Promise<void>`

*Inherited from: DownloadTask.process*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/installer/downloadTask.ts#L20" target="_blank" rel="noreferrer">packages/installer/downloadTask.ts:20</a>
</p>


### resume

```ts
resume(): Promise<void>
```
#### Return Type

- `Promise<void>`

*Inherited from: DownloadTask.resume*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L146" target="_blank" rel="noreferrer">packages/task/index.ts:146</a>
</p>


### resumeTask <Badge type="warning" text="protected" />

```ts
resumeTask(): Promise<void>
```
#### Return Type

- `Promise<void>`

*Inherited from: DownloadTask.resumeTask*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L253" target="_blank" rel="noreferrer">packages/task/index.ts:253</a>
</p>


### runTask <Badge type="warning" text="protected" />

```ts
runTask(): Promise<void>
```
#### Return Type

- `Promise<void>`

*Inherited from: DownloadTask.runTask*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L260" target="_blank" rel="noreferrer">packages/task/index.ts:260</a>
</p>


### setName

```ts
setName(name: string, param: object): InstallJarTask
```
#### Parameters

- **name**: `string`
- **param**: `object`
#### Return Type

- `InstallJarTask`

*Inherited from: DownloadTask.setName*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L111" target="_blank" rel="noreferrer">packages/task/index.ts:111</a>
</p>


### start

```ts
start(context: TaskContext, parent: Task<any>): void
```
#### Parameters

- **context**: `TaskContext`
- **parent**: `Task<any>`
#### Return Type

- `void`

*Inherited from: DownloadTask.start*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L167" target="_blank" rel="noreferrer">packages/task/index.ts:167</a>
</p>


### startAndWait

```ts
startAndWait(context: TaskContext, parent: Task<any>): Promise<void>
```
#### Parameters

- **context**: `TaskContext`
- **parent**: `Task<any>`
#### Return Type

- `Promise<void>`

*Inherited from: DownloadTask.startAndWait*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L198" target="_blank" rel="noreferrer">packages/task/index.ts:198</a>
</p>


### update <Badge type="warning" text="protected" />

```ts
update(chunkSize: number): void
```
#### Parameters

- **chunkSize**: `number`
#### Return Type

- `void`

*Inherited from: DownloadTask.update*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L203" target="_blank" rel="noreferrer">packages/task/index.ts:203</a>
</p>


### wait

```ts
wait(): Promise<void>
```
#### Return Type

- `Promise<void>`

*Inherited from: DownloadTask.wait*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L163" target="_blank" rel="noreferrer">packages/task/index.ts:163</a>
</p>


