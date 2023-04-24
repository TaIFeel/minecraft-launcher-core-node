# Class JsonValidator

## 🏭 Constructors

### constructor

```ts
new JsonValidator(): JsonValidator
```
#### Return Type

- `JsonValidator`


## 🔧 Methods

### validate

```ts
validate(fd: FileHandle, destination: string, url: string): Promise<void>
```
Validate the download result. It should throw ``ValidationError`` if validation failed.
#### Parameters

- **fd**: `FileHandle`
The file desciprtor
- **destination**: `string`
The result file
- **url**: `string`
The url where the file downloaded from
#### Return Type

- `Promise<void>`

<p style="font-size: 14px; color: var(--vp-c-text-2)">
<strong>Defined in:</strong> <a href="https://github.com/voxelum/minecraft-launcher-core-node/blob/master/packages/file-transfer/validator.ts#L52" target="_blank" rel="noreferrer">packages/file-transfer/validator.ts:52</a>
</p>


