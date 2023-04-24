# Class ResolvedNative

Represent a native libraries provided by Minecraft
## 🏭 Constructors

### constructor

```ts
new ResolvedNative(name: string, info: LibraryInfo, download: Artifact, extractExclude: string[]): ResolvedNative
```
#### Parameters

- **name**: `string`
- **info**: `LibraryInfo`
- **download**: `Artifact`
- **extractExclude**: `string[]`
#### Return Type

- `ResolvedNative`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/core/version.ts#L247" target="_blank" rel="noreferrer">packages/core/version.ts:247</a>
</p>


## 🏷️ Properties

### artifactId <Badge type="tip" text="readonly" />

```ts
artifactId: string
```
*Inherited from: ResolvedLibrary.artifactId*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/core/version.ts#L220" target="_blank" rel="noreferrer">packages/core/version.ts:220</a>
</p>


### checksums <Badge type="info" text="optional" /> <Badge type="tip" text="readonly" />

```ts
checksums: string[]
```
*Inherited from: ResolvedLibrary.checksums*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/core/version.ts#L230" target="_blank" rel="noreferrer">packages/core/version.ts:230</a>
</p>


### classifier <Badge type="tip" text="readonly" />

```ts
classifier: string
```
The classifier. Normally, this is empty. For forge, it can be like ``universal``, ``installer``.
*Inherited from: ResolvedLibrary.classifier*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/core/version.ts#L224" target="_blank" rel="noreferrer">packages/core/version.ts:224</a>
</p>


### clientreq <Badge type="info" text="optional" /> <Badge type="tip" text="readonly" />

```ts
clientreq: boolean
```
*Inherited from: ResolvedLibrary.clientreq*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/core/version.ts#L232" target="_blank" rel="noreferrer">packages/core/version.ts:232</a>
</p>


### download <Badge type="tip" text="readonly" />

```ts
download: Artifact
```
*Inherited from: ResolvedLibrary.download*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/core/version.ts#L229" target="_blank" rel="noreferrer">packages/core/version.ts:229</a>
</p>


### extractExclude <Badge type="info" text="optional" /> <Badge type="tip" text="readonly" />

```ts
extractExclude: string[]
```
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/core/version.ts#L250" target="_blank" rel="noreferrer">packages/core/version.ts:250</a>
</p>


### groupId <Badge type="tip" text="readonly" />

```ts
groupId: string
```
*Inherited from: ResolvedLibrary.groupId*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/core/version.ts#L219" target="_blank" rel="noreferrer">packages/core/version.ts:219</a>
</p>


### isSnapshot <Badge type="tip" text="readonly" />

```ts
isSnapshot: boolean
```
*Inherited from: ResolvedLibrary.isSnapshot*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/core/version.ts#L222" target="_blank" rel="noreferrer">packages/core/version.ts:222</a>
</p>


### name <Badge type="tip" text="readonly" />

```ts
name: string
```
The original maven name of this library
*Inherited from: ResolvedLibrary.name*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/core/version.ts#L227" target="_blank" rel="noreferrer">packages/core/version.ts:227</a>
</p>


### path <Badge type="tip" text="readonly" />

```ts
path: string
```
The maven path.
*Inherited from: ResolvedLibrary.path*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/core/version.ts#L225" target="_blank" rel="noreferrer">packages/core/version.ts:225</a>
</p>


### serverreq <Badge type="info" text="optional" /> <Badge type="tip" text="readonly" />

```ts
serverreq: boolean
```
*Inherited from: ResolvedLibrary.serverreq*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/core/version.ts#L231" target="_blank" rel="noreferrer">packages/core/version.ts:231</a>
</p>


### type <Badge type="tip" text="readonly" />

```ts
type: string
```
The file extension. Default is ``jar``. Some files in forge are ``zip``.
*Inherited from: ResolvedLibrary.type*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/core/version.ts#L223" target="_blank" rel="noreferrer">packages/core/version.ts:223</a>
</p>


### version <Badge type="tip" text="readonly" />

```ts
version: string
```
*Inherited from: ResolvedLibrary.version*

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/core/version.ts#L221" target="_blank" rel="noreferrer">packages/core/version.ts:221</a>
</p>


