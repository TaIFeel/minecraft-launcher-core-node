# Class ModrinthV2Client


## 🏭 Constructors

### constructor

```ts
new ModrinthV2Client(options: ModrinthClientOptions): ModrinthV2Client
```
#### Parameters

- **options**: `ModrinthClientOptions`
#### Return Type

- `ModrinthV2Client`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/modrinth/index.ts#L177" target="_blank" rel="noreferrer">packages/modrinth/index.ts:177</a>
</p>


## 🏷️ Properties

### baseUrl <Badge type="danger" text="private" />

```ts
baseUrl: string
```
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/modrinth/index.ts#L173" target="_blank" rel="noreferrer">packages/modrinth/index.ts:173</a>
</p>


### dispatcher <Badge type="danger" text="private" /> <Badge type="info" text="optional" />

```ts
dispatcher: Dispatcher
```
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/modrinth/index.ts#L174" target="_blank" rel="noreferrer">packages/modrinth/index.ts:174</a>
</p>


### headers <Badge type="danger" text="private" />

```ts
headers: Record<string, string>
```
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/modrinth/index.ts#L175" target="_blank" rel="noreferrer">packages/modrinth/index.ts:175</a>
</p>


## 🔧 Methods

### getCategoryTags

```ts
getCategoryTags(signal: AbortSignal): Promise<Category[]>
```

#### Parameters

- **signal**: `AbortSignal`
#### Return Type

- `Promise<Category[]>`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/modrinth/index.ts#L347" target="_blank" rel="noreferrer">packages/modrinth/index.ts:347</a>
</p>


### getGameVersionTags

```ts
getGameVersionTags(signal: AbortSignal): Promise<GameVersion[]>
```

#### Parameters

- **signal**: `AbortSignal`
#### Return Type

- `Promise<GameVersion[]>`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/modrinth/index.ts#L364" target="_blank" rel="noreferrer">packages/modrinth/index.ts:364</a>
</p>


### getLatestProjectVersion

```ts
getLatestProjectVersion(sha1: string, __namedParameters: Object= {}, signal: AbortSignal): Promise<ProjectVersion>
```

#### Parameters

- **sha1**: `string`
- **__namedParameters**: `Object`
- **signal**: `AbortSignal`
#### Return Type

- `Promise<ProjectVersion>`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/modrinth/index.ts#L307" target="_blank" rel="noreferrer">packages/modrinth/index.ts:307</a>
</p>


### getLicenseTags

```ts
getLicenseTags(signal: AbortSignal): Promise<License[]>
```

#### Parameters

- **signal**: `AbortSignal`
#### Return Type

- `Promise<License[]>`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/modrinth/index.ts#L330" target="_blank" rel="noreferrer">packages/modrinth/index.ts:330</a>
</p>


### getLoaderTags

```ts
getLoaderTags(signal: AbortSignal): Promise<Loader[]>
```

#### Parameters

- **signal**: `AbortSignal`
#### Return Type

- `Promise<Loader[]>`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/modrinth/index.ts#L381" target="_blank" rel="noreferrer">packages/modrinth/index.ts:381</a>
</p>


### getProject

```ts
getProject(projectId: string, signal: AbortSignal): Promise<Project>
```

#### Parameters

- **projectId**: `string`
- **signal**: `AbortSignal`
#### Return Type

- `Promise<Project>`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/modrinth/index.ts#L209" target="_blank" rel="noreferrer">packages/modrinth/index.ts:209</a>
</p>


### getProjectTeamMembers

```ts
getProjectTeamMembers(projectId: string, signal: AbortSignal): Promise<TeamMember[]>
```

#### Parameters

- **projectId**: `string`
- **signal**: `AbortSignal`
#### Return Type

- `Promise<TeamMember[]>`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/modrinth/index.ts#L398" target="_blank" rel="noreferrer">packages/modrinth/index.ts:398</a>
</p>


### getProjectVersion

```ts
getProjectVersion(versionId: string, signal: AbortSignal): Promise<ProjectVersion>
```

#### Parameters

- **versionId**: `string`
- **signal**: `AbortSignal`
#### Return Type

- `Promise<ProjectVersion>`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/modrinth/index.ts#L247" target="_blank" rel="noreferrer">packages/modrinth/index.ts:247</a>
</p>


### getProjectVersions

```ts
getProjectVersions(projectId: string, __namedParameters: Object= {}, signal: AbortSignal): Promise<ProjectVersion[]>
```

#### Parameters

- **projectId**: `string`
- **__namedParameters**: `Object`
- **signal**: `AbortSignal`
#### Return Type

- `Promise<ProjectVersion[]>`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/modrinth/index.ts#L227" target="_blank" rel="noreferrer">packages/modrinth/index.ts:227</a>
</p>


### getProjectVersionsByHash

```ts
getProjectVersionsByHash(hashes: string[], algorithm: string= 'sha1', signal: AbortSignal): Promise<Record<string, ProjectVersion>>
```

#### Parameters

- **hashes**: `string[]`
- **algorithm**: `string`
- **signal**: `AbortSignal`
#### Return Type

- `Promise<Record<string, ProjectVersion>>`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/modrinth/index.ts#L282" target="_blank" rel="noreferrer">packages/modrinth/index.ts:282</a>
</p>


### getProjectVersionsById

```ts
getProjectVersionsById(ids: string[], signal: AbortSignal): Promise<ProjectVersion[]>
```

#### Parameters

- **ids**: `string[]`
- **signal**: `AbortSignal`
#### Return Type

- `Promise<ProjectVersion[]>`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/modrinth/index.ts#L264" target="_blank" rel="noreferrer">packages/modrinth/index.ts:264</a>
</p>


### getUser

```ts
getUser(id: string, signal: AbortSignal): Promise<User>
```

#### Parameters

- **id**: `string`
- **signal**: `AbortSignal`
#### Return Type

- `Promise<User>`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/modrinth/index.ts#L415" target="_blank" rel="noreferrer">packages/modrinth/index.ts:415</a>
</p>


### getUserProjects

```ts
getUserProjects(id: string, signal: AbortSignal): Promise<Project[]>
```

#### Parameters

- **id**: `string`
- **signal**: `AbortSignal`
#### Return Type

- `Promise<Project[]>`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/modrinth/index.ts#L432" target="_blank" rel="noreferrer">packages/modrinth/index.ts:432</a>
</p>


### searchProjects

```ts
searchProjects(options: SearchProjectOptions, signal: AbortSignal): Promise<SearchResult>
```

#### Parameters

- **options**: `SearchProjectOptions`
- **signal**: `AbortSignal`
#### Return Type

- `Promise<SearchResult>`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/modrinth/index.ts#L186" target="_blank" rel="noreferrer">packages/modrinth/index.ts:186</a>
</p>


