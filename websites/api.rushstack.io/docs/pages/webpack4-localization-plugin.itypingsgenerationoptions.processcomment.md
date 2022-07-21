---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/webpack4-localization-plugin](./webpack4-localization-plugin.md) &gt; [ITypingsGenerationOptions](./webpack4-localization-plugin.itypingsgenerationoptions.md) &gt; [processComment](./webpack4-localization-plugin.itypingsgenerationoptions.processcomment.md)

## ITypingsGenerationOptions.processComment property

Optionally, provide a function that will process string comments. The returned value will become the TSDoc comment for the string in the typings.

**Signature:**

```typescript
processComment?: (comment: string | undefined, resxFilePath: string, stringName: string) => string | undefined;
```