# Interface Task

## 🏷️ Properties

### context <Badge type="tip" text="readonly" />

```ts
context: undefined | TaskContext
```
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L45" target="_blank" rel="noreferrer">packages/task/index.ts:45</a>
</p>


### from <Badge type="tip" text="readonly" />

```ts
from: undefined | string
```
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L35" target="_blank" rel="noreferrer">packages/task/index.ts:35</a>
</p>


### id <Badge type="tip" text="readonly" />

```ts
id: number
```
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L30" target="_blank" rel="noreferrer">packages/task/index.ts:30</a>
</p>


### isCancelled <Badge type="tip" text="readonly" />

```ts
isCancelled: boolean
```
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L39" target="_blank" rel="noreferrer">packages/task/index.ts:39</a>
</p>


### isDone <Badge type="tip" text="readonly" />

```ts
isDone: boolean
```
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L41" target="_blank" rel="noreferrer">packages/task/index.ts:41</a>
</p>


### isPaused <Badge type="tip" text="readonly" />

```ts
isPaused: boolean
```
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L40" target="_blank" rel="noreferrer">packages/task/index.ts:40</a>
</p>


### isRunning <Badge type="tip" text="readonly" />

```ts
isRunning: boolean
```
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L42" target="_blank" rel="noreferrer">packages/task/index.ts:42</a>
</p>


### name <Badge type="tip" text="readonly" />

```ts
name: string
```
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L31" target="_blank" rel="noreferrer">packages/task/index.ts:31</a>
</p>


### param <Badge type="tip" text="readonly" />

```ts
param: Record<string, any>
```
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L32" target="_blank" rel="noreferrer">packages/task/index.ts:32</a>
</p>


### parent <Badge type="tip" text="readonly" />

```ts
parent: undefined | Task<any>
```
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L46" target="_blank" rel="noreferrer">packages/task/index.ts:46</a>
</p>


### path <Badge type="tip" text="readonly" />

```ts
path: string
```
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L38" target="_blank" rel="noreferrer">packages/task/index.ts:38</a>
</p>


### progress <Badge type="tip" text="readonly" />

```ts
progress: number
```
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L33" target="_blank" rel="noreferrer">packages/task/index.ts:33</a>
</p>


### state <Badge type="tip" text="readonly" />

```ts
state: TaskState
```
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L43" target="_blank" rel="noreferrer">packages/task/index.ts:43</a>
</p>


### to <Badge type="tip" text="readonly" />

```ts
to: undefined | string
```
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L36" target="_blank" rel="noreferrer">packages/task/index.ts:36</a>
</p>


### total <Badge type="tip" text="readonly" />

```ts
total: number
```
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L34" target="_blank" rel="noreferrer">packages/task/index.ts:34</a>
</p>


## 🔧 Methods

### cancel

```ts
cancel(): Promise<void>
```
#### Return Type

- `Promise<void>`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L50" target="_blank" rel="noreferrer">packages/task/index.ts:50</a>
</p>


### map

```ts
map(transform: Transform<Task<T>, N>): Task<N>
```
#### Parameters

- **transform**: `Transform<Task<T>, N>`
#### Return Type

- `Task<N>`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L57" target="_blank" rel="noreferrer">packages/task/index.ts:57</a>
</p>


### onChildUpdate

```ts
onChildUpdate(chunkSize: number): void
```
#### Parameters

- **chunkSize**: `number`
#### Return Type

- `void`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L55" target="_blank" rel="noreferrer">packages/task/index.ts:55</a>
</p>


### pause

```ts
pause(): Promise<void>
```
#### Return Type

- `Promise<void>`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L48" target="_blank" rel="noreferrer">packages/task/index.ts:48</a>
</p>


### resume

```ts
resume(): Promise<void>
```
#### Return Type

- `Promise<void>`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L49" target="_blank" rel="noreferrer">packages/task/index.ts:49</a>
</p>


### setName

```ts
setName(name: string, param: Record<string, any>): Task<T>
```
#### Parameters

- **name**: `string`
- **param**: `Record<string, any>`
#### Return Type

- `Task<T>`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L59" target="_blank" rel="noreferrer">packages/task/index.ts:59</a>
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

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L51" target="_blank" rel="noreferrer">packages/task/index.ts:51</a>
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

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L53" target="_blank" rel="noreferrer">packages/task/index.ts:53</a>
</p>


### wait

```ts
wait(): Promise<T>
```
#### Return Type

- `Promise<T>`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/task/index.ts#L52" target="_blank" rel="noreferrer">packages/task/index.ts:52</a>
</p>


