# Class PostProcessingTask

Post process the post processors from ``InstallProfile``.
## 🏭 Constructors

### constructor

```ts
new PostProcessingTask(processors: PostProcessor[], minecraft: MinecraftFolder, java: SpawnJavaOptions): PostProcessingTask
```
#### Parameters

- **processors**: `PostProcessor[]`
- **minecraft**: `MinecraftFolder`
- **java**: `SpawnJavaOptions`
#### Return Type

- `PostProcessingTask`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/installer/profile.ts#L217" target="_blank" rel="noreferrer">packages/installer/profile.ts:217</a>
</p>


## 🏷️ Properties

### _from <Badge type="warning" text="protected" />

```ts
_from: undefined | string
```
*Inherited from: AbortableTask._from*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L89" target="_blank" rel="noreferrer">packages/task/index.ts:89</a>
</p>


### _id <Badge type="warning" text="protected" />

```ts
_id: number = 0
```
*Inherited from: AbortableTask._id*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L94" target="_blank" rel="noreferrer">packages/task/index.ts:94</a>
</p>


### _path <Badge type="warning" text="protected" />

```ts
_path: string = ''
```
*Inherited from: AbortableTask._path*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L93" target="_blank" rel="noreferrer">packages/task/index.ts:93</a>
</p>


### _pausing <Badge type="warning" text="protected" />

```ts
_pausing: Promise<void> = ...
```
*Inherited from: AbortableTask._pausing*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L227" target="_blank" rel="noreferrer">packages/task/index.ts:227</a>
</p>


### _progress <Badge type="warning" text="protected" />

```ts
_progress: number = 0
```
*Inherited from: AbortableTask._progress*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L91" target="_blank" rel="noreferrer">packages/task/index.ts:91</a>
</p>


### _promise <Badge type="warning" text="protected" />

```ts
_promise: Promise<void>
```
*Inherited from: AbortableTask._promise*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L84" target="_blank" rel="noreferrer">packages/task/index.ts:84</a>
</p>


### _state <Badge type="warning" text="protected" />

```ts
_state: TaskState = TaskState.Idle
```
*Inherited from: AbortableTask._state*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L83" target="_blank" rel="noreferrer">packages/task/index.ts:83</a>
</p>


### _to <Badge type="warning" text="protected" />

```ts
_to: undefined | string
```
*Inherited from: AbortableTask._to*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L90" target="_blank" rel="noreferrer">packages/task/index.ts:90</a>
</p>


### _total <Badge type="warning" text="protected" />

```ts
_total: number = -1
```
*Inherited from: AbortableTask._total*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L92" target="_blank" rel="noreferrer">packages/task/index.ts:92</a>
</p>


### context

```ts
context: TaskContext = {}
```
*Inherited from: AbortableTask.context*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L97" target="_blank" rel="noreferrer">packages/task/index.ts:97</a>
</p>


### java <Badge type="danger" text="private" />

```ts
java: SpawnJavaOptions
```
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/installer/profile.ts#L217" target="_blank" rel="noreferrer">packages/installer/profile.ts:217</a>
</p>


### minecraft <Badge type="danger" text="private" />

```ts
minecraft: MinecraftFolder
```
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/installer/profile.ts#L217" target="_blank" rel="noreferrer">packages/installer/profile.ts:217</a>
</p>


### name <Badge type="tip" text="readonly" />

```ts
name: string = 'postProcessing'
```
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/installer/profile.ts#L211" target="_blank" rel="noreferrer">packages/installer/profile.ts:211</a>
</p>


### param

```ts
param: object = {}
```
*Inherited from: AbortableTask.param*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L100" target="_blank" rel="noreferrer">packages/task/index.ts:100</a>
</p>


### parent

```ts
parent: undefined | Task<any>
```
*Inherited from: AbortableTask.parent*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L96" target="_blank" rel="noreferrer">packages/task/index.ts:96</a>
</p>


### pointer <Badge type="danger" text="private" />

```ts
pointer: number = 0
```
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/installer/profile.ts#L213" target="_blank" rel="noreferrer">packages/installer/profile.ts:213</a>
</p>


### processors <Badge type="danger" text="private" />

```ts
processors: PostProcessor[]
```
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/installer/profile.ts#L217" target="_blank" rel="noreferrer">packages/installer/profile.ts:217</a>
</p>


### reject <Badge type="warning" text="protected" />

```ts
reject: Function
```
*Inherited from: AbortableTask.reject*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L87" target="_blank" rel="noreferrer">packages/task/index.ts:87</a>
</p>


### resolve <Badge type="warning" text="protected" />

```ts
resolve: Function
```
*Inherited from: AbortableTask.resolve*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L86" target="_blank" rel="noreferrer">packages/task/index.ts:86</a>
</p>


### resultOrError <Badge type="warning" text="protected" />

```ts
resultOrError: any
```
*Inherited from: AbortableTask.resultOrError*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L102" target="_blank" rel="noreferrer">packages/task/index.ts:102</a>
</p>


## 🔑 Accessors

### from

*Inherited from: AbortableTask.from*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L130" target="_blank" rel="noreferrer">packages/task/index.ts:130</a>
</p>


### id

*Inherited from: AbortableTask.id*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L125" target="_blank" rel="noreferrer">packages/task/index.ts:125</a>
</p>


### isCancelled

*Inherited from: AbortableTask.isCancelled*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L133" target="_blank" rel="noreferrer">packages/task/index.ts:133</a>
</p>


### isDone

*Inherited from: AbortableTask.isDone*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L135" target="_blank" rel="noreferrer">packages/task/index.ts:135</a>
</p>


### isPaused

*Inherited from: AbortableTask.isPaused*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L134" target="_blank" rel="noreferrer">packages/task/index.ts:134</a>
</p>


### isRunning

*Inherited from: AbortableTask.isRunning*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L136" target="_blank" rel="noreferrer">packages/task/index.ts:136</a>
</p>


### path

*Inherited from: AbortableTask.path*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L126" target="_blank" rel="noreferrer">packages/task/index.ts:126</a>
</p>


### progress

*Inherited from: AbortableTask.progress*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L127" target="_blank" rel="noreferrer">packages/task/index.ts:127</a>
</p>


### state

*Inherited from: AbortableTask.state*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L131" target="_blank" rel="noreferrer">packages/task/index.ts:131</a>
</p>


### to

*Inherited from: AbortableTask.to*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L129" target="_blank" rel="noreferrer">packages/task/index.ts:129</a>
</p>


### total

*Inherited from: AbortableTask.total*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L128" target="_blank" rel="noreferrer">packages/task/index.ts:128</a>
</p>


## 🔧 Methods

### _abort <Badge type="danger" text="private" />

```ts
_abort(): void
```
#### Return Type

- `void`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/installer/profile.ts#L215" target="_blank" rel="noreferrer">packages/installer/profile.ts:215</a>
</p>


### _onAborted <Badge type="warning" text="protected" />

```ts
_onAborted(): void
```
#### Return Type

- `void`

*Inherited from: AbortableTask._onAborted*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L229" target="_blank" rel="noreferrer">packages/task/index.ts:229</a>
</p>


### _onResume <Badge type="warning" text="protected" />

```ts
_onResume(): void
```
#### Return Type

- `void`

*Inherited from: AbortableTask._onResume*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L230" target="_blank" rel="noreferrer">packages/task/index.ts:230</a>
</p>


### _unpause <Badge type="warning" text="protected" />

```ts
_unpause(): void
```
#### Return Type

- `void`

*Inherited from: AbortableTask._unpause*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L228" target="_blank" rel="noreferrer">packages/task/index.ts:228</a>
</p>


### abort <Badge type="warning" text="protected" />

```ts
abort(isCancelled: boolean): Promise<void>
```
#### Parameters

- **isCancelled**: `boolean`
#### Return Type

- `Promise<void>`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/installer/profile.ts#L308" target="_blank" rel="noreferrer">packages/installer/profile.ts:308</a>
</p>


### cancel

```ts
cancel(): Promise<void>
```
#### Return Type

- `Promise<void>`

*Inherited from: AbortableTask.cancel*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L154" target="_blank" rel="noreferrer">packages/task/index.ts:154</a>
</p>


### cancelTask <Badge type="warning" text="protected" />

```ts
cancelTask(): Promise<void>
```
#### Return Type

- `Promise<void>`

*Inherited from: AbortableTask.cancelTask*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L236" target="_blank" rel="noreferrer">packages/task/index.ts:236</a>
</p>


### findMainClass <Badge type="warning" text="protected" />

```ts
findMainClass(lib: string): Promise<string>
```
#### Parameters

- **lib**: `string`
#### Return Type

- `Promise<string>`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/installer/profile.ts#L223" target="_blank" rel="noreferrer">packages/installer/profile.ts:223</a>
</p>


### get

```ts
get(): void
```
#### Return Type

- `void`

*Inherited from: AbortableTask.get*

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

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/installer/profile.ts#L313" target="_blank" rel="noreferrer">packages/installer/profile.ts:313</a>
</p>


### isInvalid <Badge type="warning" text="protected" />

```ts
isInvalid(outputs: Object): Promise<boolean>
```
#### Parameters

- **outputs**: `Object`
#### Return Type

- `Promise<boolean>`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/installer/profile.ts#L248" target="_blank" rel="noreferrer">packages/installer/profile.ts:248</a>
</p>


### map

```ts
map(transform: Transform<PostProcessingTask, N>): Task<N>
```
#### Parameters

- **transform**: `Transform<PostProcessingTask, N>`
#### Return Type

- `Task<N>`

*Inherited from: AbortableTask.map*

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

*Inherited from: AbortableTask.onChildUpdate*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L208" target="_blank" rel="noreferrer">packages/task/index.ts:208</a>
</p>


### pause

```ts
pause(): Promise<void>
```
#### Return Type

- `Promise<void>`

*Inherited from: AbortableTask.pause*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L138" target="_blank" rel="noreferrer">packages/task/index.ts:138</a>
</p>


### pauseTask <Badge type="warning" text="protected" />

```ts
pauseTask(): Promise<void>
```
#### Return Type

- `Promise<void>`

*Inherited from: AbortableTask.pauseTask*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L243" target="_blank" rel="noreferrer">packages/task/index.ts:243</a>
</p>


### postProcess <Badge type="warning" text="protected" />

```ts
postProcess(mc: MinecraftFolder, proc: PostProcessor, javaOptions: SpawnJavaOptions): Promise<void>
```
#### Parameters

- **mc**: `MinecraftFolder`
- **proc**: `PostProcessor`
- **javaOptions**: `SpawnJavaOptions`
#### Return Type

- `Promise<void>`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/installer/profile.ts#L259" target="_blank" rel="noreferrer">packages/installer/profile.ts:259</a>
</p>


### process <Badge type="warning" text="protected" />

```ts
process(): Promise<void>
```
#### Return Type

- `Promise<void>`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/installer/profile.ts#L285" target="_blank" rel="noreferrer">packages/installer/profile.ts:285</a>
</p>


### resume

```ts
resume(): Promise<void>
```
#### Return Type

- `Promise<void>`

*Inherited from: AbortableTask.resume*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L146" target="_blank" rel="noreferrer">packages/task/index.ts:146</a>
</p>


### resumeTask <Badge type="warning" text="protected" />

```ts
resumeTask(): Promise<void>
```
#### Return Type

- `Promise<void>`

*Inherited from: AbortableTask.resumeTask*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L253" target="_blank" rel="noreferrer">packages/task/index.ts:253</a>
</p>


### runTask <Badge type="warning" text="protected" />

```ts
runTask(): Promise<void>
```
#### Return Type

- `Promise<void>`

*Inherited from: AbortableTask.runTask*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L260" target="_blank" rel="noreferrer">packages/task/index.ts:260</a>
</p>


### setName

```ts
setName(name: string, param: object): PostProcessingTask
```
#### Parameters

- **name**: `string`
- **param**: `object`
#### Return Type

- `PostProcessingTask`

*Inherited from: AbortableTask.setName*

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

*Inherited from: AbortableTask.start*

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

*Inherited from: AbortableTask.startAndWait*

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

*Inherited from: AbortableTask.update*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L203" target="_blank" rel="noreferrer">packages/task/index.ts:203</a>
</p>


### wait

```ts
wait(): Promise<void>
```
#### Return Type

- `Promise<void>`

*Inherited from: AbortableTask.wait*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L163" target="_blank" rel="noreferrer">packages/task/index.ts:163</a>
</p>


