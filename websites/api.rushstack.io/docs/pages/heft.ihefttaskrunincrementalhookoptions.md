---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/heft](./heft.md) &gt; [IHeftTaskRunIncrementalHookOptions](./heft.ihefttaskrunincrementalhookoptions.md)

## IHeftTaskRunIncrementalHookOptions interface

Options provided to the 'runIncremental' hook.

**Signature:**

```typescript
export interface IHeftTaskRunIncrementalHookOptions extends IHeftTaskRunHookOptions 
```
**Extends:** [IHeftTaskRunHookOptions](./heft.ihefttaskrunhookoptions.md)

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [requestRun](./heft.ihefttaskrunincrementalhookoptions.requestrun.md) | <code>readonly</code> | () =&gt; void | A callback that can be invoked to tell the Heft runtime to schedule an incremental run of this task. If a run is already pending, does nothing. |
|  [watchGlobAsync](./heft.ihefttaskrunincrementalhookoptions.watchglobasync.md) | <code>readonly</code> | [WatchGlobFn](./heft.watchglobfn.md) | <p>Reads the specified globs and returns the result, filtering out files that have not changed since the last execution. All file system calls while reading the glob are tracked and will be watched for changes.</p><p>If a change to the monitored files is detected, the task will be scheduled for re-execution.</p> |
