# Interface SearchProjectOptions

## 🏷️ Properties

### facets <Badge type="info" text="optional" />

```ts
facets: string
```
The recommended way of filtering search results. [Learn more about using facets](https://docs.modrinth.com/docs/tutorials/search).

 "categories" "versions" "license" "project_type"
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/modrinth/index.ts#L94" target="_blank" rel="noreferrer">packages/modrinth/index.ts:94</a>
</p>


### filter <Badge type="info" text="optional" />

```ts
filter: string
```
A list of filters relating to the properties of a project. Use filters when there isn't an available facet for your needs. [More information](https://docs.meilisearch.com/reference/features/filtering.html)
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/modrinth/index.ts#L100" target="_blank" rel="noreferrer">packages/modrinth/index.ts:100</a>
</p>


### index <Badge type="info" text="optional" />

```ts
index: string
```
What the results are sorted by

 "relevance" "downloads" "follows" "newest" "updated"
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/modrinth/index.ts#L108" target="_blank" rel="noreferrer">packages/modrinth/index.ts:108</a>
</p>


### limit <Badge type="info" text="optional" />

```ts
limit: number
```
The number of mods returned by the search
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/modrinth/index.ts#L118" target="_blank" rel="noreferrer">packages/modrinth/index.ts:118</a>
</p>


### offset <Badge type="info" text="optional" />

```ts
offset: number
```
The offset into the search; skips this number of results
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/modrinth/index.ts#L113" target="_blank" rel="noreferrer">packages/modrinth/index.ts:113</a>
</p>


### query <Badge type="info" text="optional" />

```ts
query: string
```
The query to search
<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/modrinth/index.ts#L87" target="_blank" rel="noreferrer">packages/modrinth/index.ts:87</a>
</p>


