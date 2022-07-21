---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/webpack4-localization-plugin](./webpack4-localization-plugin.md) &gt; [ILocalizedData](./webpack4-localization-plugin.ilocalizeddata.md) &gt; [resolveMissingTranslatedStrings](./webpack4-localization-plugin.ilocalizeddata.resolvemissingtranslatedstrings.md)

## ILocalizedData.resolveMissingTranslatedStrings property

Use this parameter to specify a function used to load translations missing from the [ILocalizedData.translatedStrings](./webpack4-localization-plugin.ilocalizeddata.translatedstrings.md) parameter.

<b>Signature:</b>

```typescript
resolveMissingTranslatedStrings?: (locales: string[], filePath: string) => IResolvedMissingTranslations;
```