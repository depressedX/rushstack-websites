---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@microsoft/rush-lib](./rush-lib.md) &gt; [RepoStateFile](./rush-lib.repostatefile.md) &gt; [loadFromFile](./rush-lib.repostatefile.loadfromfile.md)

## RepoStateFile.loadFromFile() method

Loads the repo-state.json data from the specified file path. If the file has not been created yet, then an empty object is returned.

<b>Signature:</b>

```typescript
static loadFromFile(jsonFilename: string, variant: string | undefined): RepoStateFile;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  jsonFilename | string | The path to the repo-state.json file. |
|  variant | string \| undefined | The variant currently being used by Rush. |

<b>Returns:</b>

[RepoStateFile](./rush-lib.repostatefile.md)
