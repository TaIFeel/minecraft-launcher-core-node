# Class CurseforgeV1Client

Reference the https://docs.curseforge.com/#curseforge-core-api-mods
## 🏭 Constructors

### constructor

```ts
new CurseforgeV1Client(apiKey: string, options: CurseforgeClientOptions): CurseforgeV1Client
```
#### Parameters

- **apiKey**: `string`
- **options**: `CurseforgeClientOptions`
#### Return Type

- `CurseforgeV1Client`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/curseforge/index.ts#L536" target="_blank" rel="noreferrer">packages/curseforge/index.ts:536</a>
</p>


## 🏷️ Properties

### apiKey <Badge type="danger" text="private" />

```ts
apiKey: string
```
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/curseforge/index.ts#L536" target="_blank" rel="noreferrer">packages/curseforge/index.ts:536</a>
</p>


### baseUrl <Badge type="danger" text="private" />

```ts
baseUrl: string
```
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/curseforge/index.ts#L534" target="_blank" rel="noreferrer">packages/curseforge/index.ts:534</a>
</p>


### dispatcher <Badge type="danger" text="private" /> <Badge type="info" text="optional" />

```ts
dispatcher: Dispatcher
```
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/curseforge/index.ts#L533" target="_blank" rel="noreferrer">packages/curseforge/index.ts:533</a>
</p>


### headers <Badge type="danger" text="private" />

```ts
headers: Record<string, string>
```
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/curseforge/index.ts#L532" target="_blank" rel="noreferrer">packages/curseforge/index.ts:532</a>
</p>


## 🔧 Methods

### getCategories

```ts
getCategories(signal: AbortSignal): Promise<ModCategory[]>
```

#### Parameters

- **signal**: `AbortSignal`
#### Return Type

- `Promise<ModCategory[]>`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/curseforge/index.ts#L548" target="_blank" rel="noreferrer">packages/curseforge/index.ts:548</a>
</p>


### getFiles

```ts
getFiles(fileIds: number[], signal: AbortSignal): Promise<File[]>
```

#### Parameters

- **fileIds**: `number[]`
- **signal**: `AbortSignal`
#### Return Type

- `Promise<File[]>`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/curseforge/index.ts#L680" target="_blank" rel="noreferrer">packages/curseforge/index.ts:680</a>
</p>


### getMod

```ts
getMod(modId: number, signal: AbortSignal): Promise<Mod>
```
Get the mod by mod Id.
#### Parameters

- **modId**: `number`
The id of mod
- **signal**: `AbortSignal`
#### Return Type

- `Promise<Mod>`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/curseforge/index.ts#L572" target="_blank" rel="noreferrer">packages/curseforge/index.ts:572</a>
</p>


### getModDescription

```ts
getModDescription(modId: number, signal: AbortSignal): Promise<string>
```

#### Parameters

- **modId**: `number`
- **signal**: `AbortSignal`
#### Return Type

- `Promise<string>`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/curseforge/index.ts#L592" target="_blank" rel="noreferrer">packages/curseforge/index.ts:592</a>
</p>


### getModFile

```ts
getModFile(modId: number, fileId: number, signal: AbortSignal): Promise<File>
```

#### Parameters

- **modId**: `number`
- **fileId**: `number`
- **signal**: `AbortSignal`
#### Return Type

- `Promise<File>`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/curseforge/index.ts#L637" target="_blank" rel="noreferrer">packages/curseforge/index.ts:637</a>
</p>


### getModFiles

```ts
getModFiles(options: GetModFilesOptions, signal: AbortSignal): Promise<Object>
```

#### Parameters

- **options**: `GetModFilesOptions`
- **signal**: `AbortSignal`
#### Return Type

- `Promise<Object>`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/curseforge/index.ts#L612" target="_blank" rel="noreferrer">packages/curseforge/index.ts:612</a>
</p>


### getMods

```ts
getMods(modIds: number[], signal: AbortSignal): Promise<Mod[]>
```

#### Parameters

- **modIds**: `number[]`
- **signal**: `AbortSignal`
#### Return Type

- `Promise<Mod[]>`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/curseforge/index.ts#L657" target="_blank" rel="noreferrer">packages/curseforge/index.ts:657</a>
</p>


### searchMods

```ts
searchMods(options: SearchOptions, signal: AbortSignal): Promise<Object>
```

#### Parameters

- **options**: `SearchOptions`
- **signal**: `AbortSignal`
#### Return Type

- `Promise<Object>`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/curseforge/index.ts#L703" target="_blank" rel="noreferrer">packages/curseforge/index.ts:703</a>
</p>


