---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/webpack4-localization-plugin](./webpack4-localization-plugin.md) &gt; [ITypingsGenerationOptions](./webpack4-localization-plugin.itypingsgenerationoptions.md)

## ITypingsGenerationOptions interface

Options for typing generation.

**Signature:**

```typescript
export interface ITypingsGenerationOptions
```

## Properties

| Property                                                                                                                | Modifiers | Type                                                                                               | Description                                                                                                                                                         |
| ----------------------------------------------------------------------------------------------------------------------- | --------- | -------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [exportAsDefault?](./webpack4-localization-plugin.itypingsgenerationoptions.exportasdefault.md)                         |           | boolean                                                                                            | <i>(Optional)</i> If this option is set to <code>true</code>, loc modules typings will be exported wrapped in a <code>default</code> property.                      |
| [generatedTsFolder](./webpack4-localization-plugin.itypingsgenerationoptions.generatedtsfolder.md)                      |           | string                                                                                             | This property specifies the folder in which <code>.d.ts</code> files for loc files should be dropped.                                                               |
| [ignoreString?](./webpack4-localization-plugin.itypingsgenerationoptions.ignorestring.md)                               |           | (resxFilePath: string, stringName: string) =&gt; boolean                                           | <i>(Optional)</i>                                                                                                                                                   |
| [processComment?](./webpack4-localization-plugin.itypingsgenerationoptions.processcomment.md)                           |           | (comment: string \| undefined, resxFilePath: string, stringName: string) =&gt; string \| undefined | <i>(Optional)</i> Optionally, provide a function that will process string comments. The returned value will become the TSDoc comment for the string in the typings. |
| [secondaryGeneratedTsFolders?](./webpack4-localization-plugin.itypingsgenerationoptions.secondarygeneratedtsfolders.md) |           | string\[\]                                                                                         | <i>(Optional)</i> Optional additional folders into which <code>.d.ts</code> files for loc files should be dropped.                                                  |
| [sourceRoot?](./webpack4-localization-plugin.itypingsgenerationoptions.sourceroot.md)                                   |           | string                                                                                             | <i>(Optional)</i> This optional property overrides the compiler context for discovery of localization files for which typings should be generated.                  |