---
aliases: "obsidian.DataAdapter.trashSystem.md"
cssclasses: hide-title
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[`DataAdapter`](obsidian.DataAdapter.md) › [`trashSystem`](obsidian.DataAdapter.trashSystem.md)

## DataAdapter.trashSystem() method

Try moving to system trash.

**Signature:**

```typescript
trashSystem(normalizedPath: string): Promise<boolean>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  <code>normalizedPath</code> | <code>string</code> | path to file/folder, use [normalizePath()](obsidian.normalizePath.md) to normalize beforehand. |

**Returns:**

`Promise``<boolean>`

Returns true if succeeded. This can fail due to system trash being disabled.

