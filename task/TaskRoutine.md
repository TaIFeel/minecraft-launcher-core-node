# Class TaskRoutine

## 🏭 Constructors

### constructor

```ts
new TaskRoutine(name: string, executor: TaskExecutor<T>, param: object= {}): TaskRoutine<T>
```
#### Parameters

- **name**: `string`
- **executor**: `TaskExecutor<T>`
- **param**: `object`
#### Return Type

- `TaskRoutine<T>`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L353" target="_blank" rel="noreferrer">packages/task/index.ts:353</a>
</p>


## 🏷️ Properties

### _from <Badge type="warning" text="protected" />

```ts
_from: undefined | string
```
*Inherited from: TaskGroup._from*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L89" target="_blank" rel="noreferrer">packages/task/index.ts:89</a>
</p>


### _id <Badge type="warning" text="protected" />

```ts
_id: number = 0
```
*Inherited from: TaskGroup._id*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L94" target="_blank" rel="noreferrer">packages/task/index.ts:94</a>
</p>


### _path <Badge type="warning" text="protected" />

```ts
_path: string = ''
```
*Inherited from: TaskGroup._path*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L93" target="_blank" rel="noreferrer">packages/task/index.ts:93</a>
</p>


### _progress <Badge type="warning" text="protected" />

```ts
_progress: number = 0
```
*Inherited from: TaskGroup._progress*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L91" target="_blank" rel="noreferrer">packages/task/index.ts:91</a>
</p>


### _promise <Badge type="warning" text="protected" />

```ts
_promise: Promise<T>
```
*Inherited from: TaskGroup._promise*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L84" target="_blank" rel="noreferrer">packages/task/index.ts:84</a>
</p>


### _state <Badge type="warning" text="protected" />

```ts
_state: TaskState = TaskState.Idle
```
*Inherited from: TaskGroup._state*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L83" target="_blank" rel="noreferrer">packages/task/index.ts:83</a>
</p>


### _to <Badge type="warning" text="protected" />

```ts
_to: undefined | string
```
*Inherited from: TaskGroup._to*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L90" target="_blank" rel="noreferrer">packages/task/index.ts:90</a>
</p>


### _total <Badge type="warning" text="protected" />

```ts
_total: number = -1
```
*Inherited from: TaskGroup._total*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L92" target="_blank" rel="noreferrer">packages/task/index.ts:92</a>
</p>


### children <Badge type="warning" text="protected" />

```ts
children: Task<any>[] = []
```
*Inherited from: TaskGroup.children*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L288" target="_blank" rel="noreferrer">packages/task/index.ts:288</a>
</p>


### context

```ts
context: TaskContext = {}
```
*Inherited from: TaskGroup.context*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L97" target="_blank" rel="noreferrer">packages/task/index.ts:97</a>
</p>


### executor <Badge type="tip" text="readonly" />

```ts
executor: TaskExecutor<T>
```
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L353" target="_blank" rel="noreferrer">packages/task/index.ts:353</a>
</p>


### name

```ts
name: string = ''
```
*Inherited from: TaskGroup.name*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L99" target="_blank" rel="noreferrer">packages/task/index.ts:99</a>
</p>


### param

```ts
param: object = {}
```
*Inherited from: TaskGroup.param*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L100" target="_blank" rel="noreferrer">packages/task/index.ts:100</a>
</p>


### parent

```ts
parent: undefined | Task<any>
```
*Inherited from: TaskGroup.parent*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L96" target="_blank" rel="noreferrer">packages/task/index.ts:96</a>
</p>


### reject <Badge type="warning" text="protected" />

```ts
reject: Function
```
*Inherited from: TaskGroup.reject*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L87" target="_blank" rel="noreferrer">packages/task/index.ts:87</a>
</p>


### resolve <Badge type="warning" text="protected" />

```ts
resolve: Function
```
*Inherited from: TaskGroup.resolve*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L86" target="_blank" rel="noreferrer">packages/task/index.ts:86</a>
</p>


### resultOrError <Badge type="warning" text="protected" />

```ts
resultOrError: any
```
*Inherited from: TaskGroup.resultOrError*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L102" target="_blank" rel="noreferrer">packages/task/index.ts:102</a>
</p>


## 🔑 Accessors

### from

*Inherited from: TaskGroup.from*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L130" target="_blank" rel="noreferrer">packages/task/index.ts:130</a>
</p>


### id

*Inherited from: TaskGroup.id*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L125" target="_blank" rel="noreferrer">packages/task/index.ts:125</a>
</p>


### isCancelled

*Inherited from: TaskGroup.isCancelled*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L133" target="_blank" rel="noreferrer">packages/task/index.ts:133</a>
</p>


### isDone

*Inherited from: TaskGroup.isDone*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L135" target="_blank" rel="noreferrer">packages/task/index.ts:135</a>
</p>


### isPaused

*Inherited from: TaskGroup.isPaused*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L134" target="_blank" rel="noreferrer">packages/task/index.ts:134</a>
</p>


### isRunning

*Inherited from: TaskGroup.isRunning*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L136" target="_blank" rel="noreferrer">packages/task/index.ts:136</a>
</p>


### path

*Inherited from: TaskGroup.path*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L126" target="_blank" rel="noreferrer">packages/task/index.ts:126</a>
</p>


### progress

*Inherited from: TaskGroup.progress*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L127" target="_blank" rel="noreferrer">packages/task/index.ts:127</a>
</p>


### state

*Inherited from: TaskGroup.state*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L131" target="_blank" rel="noreferrer">packages/task/index.ts:131</a>
</p>


### to

*Inherited from: TaskGroup.to*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L129" target="_blank" rel="noreferrer">packages/task/index.ts:129</a>
</p>


### total

*Inherited from: TaskGroup.total*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L128" target="_blank" rel="noreferrer">packages/task/index.ts:128</a>
</p>


## 🔧 Methods

### all

```ts
all(tasks: Iterable<T>, __namedParameters: Object= ...): Promise<Z[]>
```
#### Parameters

- **tasks**: `Iterable<T>`
- **__namedParameters**: `Object`
#### Return Type

- `Promise<Z[]>`

*Inherited from: TaskGroup.all*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L314" target="_blank" rel="noreferrer">packages/task/index.ts:314</a>
</p>


### cancel

```ts
cancel(): Promise<void>
```
#### Return Type

- `Promise<void>`

*Inherited from: TaskGroup.cancel*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L154" target="_blank" rel="noreferrer">packages/task/index.ts:154</a>
</p>


### cancelTask <Badge type="warning" text="protected" />

```ts
cancelTask(): Promise<void>
```
#### Return Type

- `Promise<void>`

*Inherited from: TaskGroup.cancelTask*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L302" target="_blank" rel="noreferrer">packages/task/index.ts:302</a>
</p>


### concat

```ts
concat(task: TaskRoutine<T>): Promise<T>
```
#### Parameters

- **task**: `TaskRoutine<T>`
#### Return Type

- `Promise<T>`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L358" target="_blank" rel="noreferrer">packages/task/index.ts:358</a>
</p>


### get

```ts
get(): void | T
```
#### Return Type

- `void | T`

*Inherited from: TaskGroup.get*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L117" target="_blank" rel="noreferrer">packages/task/index.ts:117</a>
</p>


### map

```ts
map(transform: Transform<TaskRoutine<T>, N>): Task<N>
```
#### Parameters

- **transform**: `Transform<TaskRoutine<T>, N>`
#### Return Type

- `Task<N>`

*Inherited from: TaskGroup.map*

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

*Inherited from: TaskGroup.onChildUpdate*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L290" target="_blank" rel="noreferrer">packages/task/index.ts:290</a>
</p>


### pause

```ts
pause(): Promise<void>
```
#### Return Type

- `Promise<void>`

*Inherited from: TaskGroup.pause*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L138" target="_blank" rel="noreferrer">packages/task/index.ts:138</a>
</p>


### pauseTask <Badge type="warning" text="protected" />

```ts
pauseTask(): Promise<void>
```
#### Return Type

- `Promise<void>`

*Inherited from: TaskGroup.pauseTask*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L306" target="_blank" rel="noreferrer">packages/task/index.ts:306</a>
</p>


### resume

```ts
resume(): Promise<void>
```
#### Return Type

- `Promise<void>`

*Inherited from: TaskGroup.resume*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L146" target="_blank" rel="noreferrer">packages/task/index.ts:146</a>
</p>


### resumeTask <Badge type="warning" text="protected" />

```ts
resumeTask(): Promise<void>
```
#### Return Type

- `Promise<void>`

*Inherited from: TaskGroup.resumeTask*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L310" target="_blank" rel="noreferrer">packages/task/index.ts:310</a>
</p>


### runTask <Badge type="warning" text="protected" />

```ts
runTask(): Promise<T>
```
#### Return Type

- `Promise<T>`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L381" target="_blank" rel="noreferrer">packages/task/index.ts:381</a>
</p>


### setName

```ts
setName(name: string, param: object): TaskRoutine<T>
```
#### Parameters

- **name**: `string`
- **param**: `object`
#### Return Type

- `TaskRoutine<T>`

*Inherited from: TaskGroup.setName*

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

*Inherited from: TaskGroup.start*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L167" target="_blank" rel="noreferrer">packages/task/index.ts:167</a>
</p>


### startAndWait

```ts
startAndWait(context: TaskContext, parent: Task<any>): Promise<T>
```
#### Parameters

- **context**: `TaskContext`
- **parent**: `Task<any>`
#### Return Type

- `Promise<T>`

*Inherited from: TaskGroup.startAndWait*

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

*Inherited from: TaskGroup.update*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L203" target="_blank" rel="noreferrer">packages/task/index.ts:203</a>
</p>


### wait

```ts
wait(): Promise<T>
```
#### Return Type

- `Promise<T>`

*Inherited from: TaskGroup.wait*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L163" target="_blank" rel="noreferrer">packages/task/index.ts:163</a>
</p>


### yield

```ts
yield(task: Task<T>): Promise<T>
```
Yield a new child task to this routine
#### Parameters

- **task**: `Task<T>`
#### Return Type

- `Promise<T>`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L373" target="_blank" rel="noreferrer">packages/task/index.ts:373</a>
</p>


