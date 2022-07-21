---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/localization-utilities](./localization-utilities.md) &gt; [IParseResxOptions](./localization-utilities.iparseresxoptions.md)

## IParseResxOptions interface

<b>Signature:</b>

```typescript
export interface IParseResxOptions extends IParseFileOptions, IParseResxOptionsBase
```

<b>Extends:</b> [IParseFileOptions](./localization-utilities.iparsefileoptions.md) , [IParseResxOptionsBase](./localization-utilities.iparseresxoptionsbase.md)

## Properties

| Property                                                                                                 | Modifiers | Type                                                                     | Description                                                                                                                                                                                                                                                        |
| -------------------------------------------------------------------------------------------------------- | --------- | ------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [content](./localization-utilities.iparsefileoptions.content.md)                                         |           | string                                                                   | (Inherited from [IParseFileOptions](./localization-utilities.iparsefileoptions.md) )                                                                                                                                                                               |
| [filePath](./localization-utilities.iparsefileoptions.filepath.md)                                       |           | string                                                                   | (Inherited from [IParseFileOptions](./localization-utilities.iparsefileoptions.md) )                                                                                                                                                                               |
| [ignoreMissingResxComments](./localization-utilities.iparseresxoptionsbase.ignoremissingresxcomments.md) |           | boolean \| undefined                                                     | (Inherited from [IParseResxOptionsBase](./localization-utilities.iparseresxoptionsbase.md) )                                                                                                                                                                       |
| [ignoreString?](./localization-utilities.iparsefileoptions.ignorestring.md)                              |           | [IgnoreStringFunction](./localization-utilities.ignorestringfunction.md) | <p><i>(Optional)</i> Optionally, provide a function that will be called for each string. If the function returns <code>true</code> the string will not be included.</p><p>(Inherited from [IParseFileOptions](./localization-utilities.iparsefileoptions.md) )</p> |
| [resxNewlineNormalization](./localization-utilities.iparseresxoptionsbase.resxnewlinenormalization.md)   |           | [NewlineKind](./node-core-library.newlinekind.md) \| undefined           | (Inherited from [IParseResxOptionsBase](./localization-utilities.iparseresxoptionsbase.md) )                                                                                                                                                                       |
| [terminal](./localization-utilities.iparseresxoptionsbase.terminal.md)                                   |           | [ITerminal](./node-core-library.iterminal.md)                            | (Inherited from [IParseResxOptionsBase](./localization-utilities.iparseresxoptionsbase.md) )                                                                                                                                                                       |