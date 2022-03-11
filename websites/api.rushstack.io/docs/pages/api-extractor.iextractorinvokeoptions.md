---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@microsoft/api-extractor](./api-extractor.md) &gt; [IExtractorInvokeOptions](./api-extractor.iextractorinvokeoptions.md)

## IExtractorInvokeOptions interface

Runtime options for Extractor.

<b>Signature:</b>

```typescript
export interface IExtractorInvokeOptions
```

## Properties

| Property                                                                                         | Type                                                                           | Description                                                                                                                                                                                                                        |
| ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [compilerState?](./api-extractor.iextractorinvokeoptions.compilerstate.md)                       | [CompilerState](./api-extractor.compilerstate.md)                              | <i>(Optional)</i> An optional TypeScript compiler state. This allows an optimization where multiple invocations of API Extractor can reuse the same TypeScript compiler analysis.                                                  |
| [localBuild?](./api-extractor.iextractorinvokeoptions.localbuild.md)                             | boolean                                                                        | <i>(Optional)</i> Indicates that API Extractor is running as part of a local build, e.g. on developer's machine.                                                                                                                   |
| [messageCallback?](./api-extractor.iextractorinvokeoptions.messagecallback.md)                   | (message: [ExtractorMessage](./api-extractor.extractormessage.md) ) =&gt; void | <i>(Optional)</i> An optional callback function that will be called for each <code>ExtractorMessage</code> before it is displayed by API Extractor. The callback can customize the message, handle it, or discard it.              |
| [showDiagnostics?](./api-extractor.iextractorinvokeoptions.showdiagnostics.md)                   | boolean                                                                        | <i>(Optional)</i> If true, API Extractor will print diagnostic information used for troubleshooting problems. These messages will be included as [ExtractorLogLevel.Verbose](./api-extractor.extractorloglevel.verbose.md) output. |
| [showVerboseMessages?](./api-extractor.iextractorinvokeoptions.showverbosemessages.md)           | boolean                                                                        | <i>(Optional)</i> If true, API Extractor will include [ExtractorLogLevel.Verbose](./api-extractor.extractorloglevel.verbose.md) messages in its output.                                                                            |
| [typescriptCompilerFolder?](./api-extractor.iextractorinvokeoptions.typescriptcompilerfolder.md) | string                                                                         | <i>(Optional)</i> Specifies an alternate folder path to be used when loading the TypeScript system typings.                                                                                                                        |