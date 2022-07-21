---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/webpack5-module-minifier-plugin](./webpack5-module-minifier-plugin.md)

## webpack5-module-minifier-plugin package

## Classes

| Class                                                                             | Description                                                                                                                                                  |
| --------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [ModuleMinifierPlugin](./webpack5-module-minifier-plugin.moduleminifierplugin.md) | Webpack plugin that minifies code on a per-module basis rather than per-asset. The actual minification is handled by the input <code>minifier</code> object. |

## Functions

| Function                                                                                                            | Description                                                                                                                                          |
| ------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| [generateLicenseFileForAsset(compilation, asset)](./webpack5-module-minifier-plugin.generatelicensefileforasset.md) | Generates a companion asset containing all extracted comments. If it is non-empty, returns a banner comment directing users to said companion asset. |

## Interfaces

| Interface                                                                                         | Description                                                                      |
| ------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- |
| [IAssetInfo](./webpack5-module-minifier-plugin.iassetinfo.md)                                     | Information about a dehydrated webpack ECMAScript asset                          |
| [IDehydratedAssets](./webpack5-module-minifier-plugin.idehydratedassets.md)                       | The set of data remaining to rehydrate in the current compilation                |
| [IFactoryMeta](./webpack5-module-minifier-plugin.ifactorymeta.md)                                 | Properties surfaced via the <code>factoryMeta</code> property on webpack modules |
| [IModuleInfo](./webpack5-module-minifier-plugin.imoduleinfo.md)                                   | Information about a minified module                                              |
| [IModuleMinifierPluginHooks](./webpack5-module-minifier-plugin.imoduleminifierpluginhooks.md)     | Hooks provided by the ModuleMinifierPlugin                                       |
| [IModuleMinifierPluginOptions](./webpack5-module-minifier-plugin.imoduleminifierpluginoptions.md) | Options to the ModuleMinifierPlugin constructor                                  |
| [IModuleMinifierPluginStats](./webpack5-module-minifier-plugin.imoduleminifierpluginstats.md)     | Statistics from the plugin. Namely module sizes.                                 |
| [IModuleStats](./webpack5-module-minifier-plugin.imodulestats.md)                                 | Module size data as a function of the target chunk.                              |
| [IPostProcessFragmentContext](./webpack5-module-minifier-plugin.ipostprocessfragmentcontext.md)   | Argument to the postProcessCodeFragment hook for the current execution context   |

## Variables

| Variable                                                                            | Description                                                                                                                                                                                                          |
| ----------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [CHUNK_MODULE_REGEX](./webpack5-module-minifier-plugin.chunk_module_regex.md)       | RegExp for replacing chunk module placeholders                                                                                                                                                                       |
| [CHUNK_MODULE_TOKEN](./webpack5-module-minifier-plugin.chunk_module_token.md)       | Token preceding a module id in the emitted asset so the minifier can operate on the Webpack runtime or chunk boilerplate in isolation                                                                                |
| [MODULE_WRAPPER_PREFIX](./webpack5-module-minifier-plugin.module_wrapper_prefix.md) | Prefix to wrap <code>function (module, **webpack_exports**, **webpack_require**) { ... }</code> so that the minifier doesn't delete it. Public because alternate Minifier implementations may wish to know about it. |
| [MODULE_WRAPPER_SUFFIX](./webpack5-module-minifier-plugin.module_wrapper_suffix.md) | Suffix to wrap <code>function (module, **webpack_exports**, **webpack_require**) { ... }</code> so that the minifier doesn't delete it. Public because alternate Minifier implementations may wish to know about it. |
| [STAGE_AFTER](./webpack5-module-minifier-plugin.stage_after.md)                     | Stage \# to use when this should be the last tap in the hook                                                                                                                                                         |
| [STAGE_BEFORE](./webpack5-module-minifier-plugin.stage_before.md)                   | Stage \# to use when this should be the first tap in the hook                                                                                                                                                        |

## Type Aliases

| Type Alias                                                    | Description                                |
| ------------------------------------------------------------- | ------------------------------------------ |
| [IAssetMap](./webpack5-module-minifier-plugin.iassetmap.md)   | A map from file names to dehydrated assets |
| [IModuleMap](./webpack5-module-minifier-plugin.imodulemap.md) | A map from module ids to minified modules  |