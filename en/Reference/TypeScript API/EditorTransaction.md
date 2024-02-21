---
aliases: "EditorTransaction.md"
cssclasses: hide-title
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[`EditorTransaction`](obsidian.EditorTransaction.md)

## EditorTransaction interface


**Signature:**

```typescript
export interface EditorTransaction 
```

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [`changes?`](obsidian.EditorTransaction.changes.md) |  | [`EditorChange`](obsidian.EditorChange.md)<code>[]</code> | _(Optional)_ |
|  [`replaceSelection?`](obsidian.EditorTransaction.replaceSelection.md) |  | <code>string</code> | _(Optional)_ |
|  [`selection?`](obsidian.EditorTransaction.selection.md) |  | [`EditorRangeOrCaret`](obsidian.EditorRangeOrCaret.md) | _(Optional)_ |
|  [`selections?`](obsidian.EditorTransaction.selections.md) |  | [`EditorRangeOrCaret`](obsidian.EditorRangeOrCaret.md)<code>[]</code> | _(Optional)_ Multiple selections, overrides <code>selection</code>. |
