# Interface MinecraftProcessWatcher

The Minecraft process watcher. You can inspect Minecraft launch state by this.

Generally, there are several cases after you call ``launch`` and get ``ChildProcess`` object

1. child process fire an error, no real process start.
2. child process started, but game crash (code is not 0).
3. cihld process started, game normally exit (code is 0).
## 🔧 Methods

### on

```ts
on(event: "error", listener: Function): MinecraftProcessWatcher
```
Fire when the process DOESN'T start at all, like "java not found".

The minecraft-kill or minecraft-exit will NOT fire after this fired.
#### Parameters

- **event**: `"error"`
- **listener**: `Function`
#### Return Type

- `MinecraftProcessWatcher`

```ts
on(event: "minecraft-exit", listener: Function): MinecraftProcessWatcher
```
Fire after Minecraft process exit.
#### Parameters

- **event**: `"minecraft-exit"`
- **listener**: `Function`
#### Return Type

- `MinecraftProcessWatcher`

```ts
on(event: "minecraft-window-ready", listener: Function): MinecraftProcessWatcher
```
Fire around the time when Minecraft window appeared in screen.

Since the Minecraft window will take time to init, this event fire when it capture some keywords from stdout.
#### Parameters

- **event**: `"minecraft-window-ready"`
- **listener**: `Function`
#### Return Type

- `MinecraftProcessWatcher`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/core/launch.ts#L454" target="_blank" rel="noreferrer">packages/core/launch.ts:454</a>, <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/core/launch.ts#L458" target="_blank" rel="noreferrer">packages/core/launch.ts:458</a>, <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/core/launch.ts#L481" target="_blank" rel="noreferrer">packages/core/launch.ts:481</a>
</p>


