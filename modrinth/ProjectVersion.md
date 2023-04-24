# Interface ProjectVersion

## 🏷️ Properties

### author_id

```ts
author_id: string
```
The ID of the author who published this version
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/modrinth/types.ts#L176" target="_blank" rel="noreferrer">packages/modrinth/types.ts:176</a>
</p>


### changelog <Badge type="info" text="optional" />

```ts
changelog: string
```
The changelog for this version of the mod.
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/modrinth/types.ts#L192" target="_blank" rel="noreferrer">packages/modrinth/types.ts:192</a>
</p>


### changelog_url <Badge type="info" text="optional" />

```ts
changelog_url: string
```
DEPRECATED A link to the changelog for this version of the mod
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/modrinth/types.ts#L196" target="_blank" rel="noreferrer">packages/modrinth/types.ts:196</a>
</p>


### date_published

```ts
date_published: string
```
The date that this version was published
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/modrinth/types.ts#L200" target="_blank" rel="noreferrer">packages/modrinth/types.ts:200</a>
</p>


### dependencies

```ts
dependencies: Object[]
```
A list of specific versions of mods that this version depends on
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/modrinth/types.ts#L216" target="_blank" rel="noreferrer">packages/modrinth/types.ts:216</a>
</p>


### downloads

```ts
downloads: number
```
The number of downloads this specific version has
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/modrinth/types.ts#L204" target="_blank" rel="noreferrer">packages/modrinth/types.ts:204</a>
</p>


### featured

```ts
featured: boolean
```
Whether the version is featured or not
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/modrinth/types.ts#L180" target="_blank" rel="noreferrer">packages/modrinth/types.ts:180</a>
</p>


### files

```ts
files: ModVersionFile[]
```
A list of files available for download for this version
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/modrinth/types.ts#L212" target="_blank" rel="noreferrer">packages/modrinth/types.ts:212</a>
</p>


### game_versions

```ts
game_versions: string[]
```
A list of versions of Minecraft that this version of the mod supports
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/modrinth/types.ts#L220" target="_blank" rel="noreferrer">packages/modrinth/types.ts:220</a>
</p>


### id

```ts
id: string
```
The ID of the version, encoded as a base62 string
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/modrinth/types.ts#L168" target="_blank" rel="noreferrer">packages/modrinth/types.ts:168</a>
</p>


### loaders

```ts
loaders: string[]
```
The mod loaders that this version supports
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/modrinth/types.ts#L224" target="_blank" rel="noreferrer">packages/modrinth/types.ts:224</a>
</p>


### name

```ts
name: string
```
The name of this version
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/modrinth/types.ts#L184" target="_blank" rel="noreferrer">packages/modrinth/types.ts:184</a>
</p>


### project_id

```ts
project_id: string
```
The ID of the project this version is for
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/modrinth/types.ts#L172" target="_blank" rel="noreferrer">packages/modrinth/types.ts:172</a>
</p>


### version_number

```ts
version_number: string
```
The version number. Ideally will follow semantic versioning
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/modrinth/types.ts#L188" target="_blank" rel="noreferrer">packages/modrinth/types.ts:188</a>
</p>


### version_type

```ts
version_type: string
```
The type of the release - alpha, beta, or release
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/modrinth/types.ts#L208" target="_blank" rel="noreferrer">packages/modrinth/types.ts:208</a>
</p>


