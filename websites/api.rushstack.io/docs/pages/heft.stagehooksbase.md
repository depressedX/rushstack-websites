---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/heft](./heft.md) &gt; [StageHooksBase](./heft.stagehooksbase.md)

## StageHooksBase class


**Signature:**

```typescript
export declare abstract class StageHooksBase<TStageProperties extends object> 
```

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [afterLoadStageConfiguration](./heft.stagehooksbase.afterloadstageconfiguration.md) | <code>readonly</code> | AsyncSeriesHook |  |
|  [loadStageConfiguration](./heft.stagehooksbase.loadstageconfiguration.md) | <code>readonly</code> | AsyncSeriesHook |  |
|  [overrideStage](./heft.stagehooksbase.overridestage.md) | <code>readonly</code> | AsyncSeriesBailHook&lt;TStageProperties&gt; | **_(BETA)_** This hook allows the stage's execution to be completely overridden. Only the last-registered plugin with an override hook provided applies. |

