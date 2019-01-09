[Home](./index) &gt; [@microsoft/rush-lib](./rush-lib.md) &gt; [RushConfiguration](./rush-lib.rushconfiguration.md) &gt; [tryGetProjectForPath](./rush-lib.rushconfiguration.trygetprojectforpath.md)

## RushConfiguration.tryGetProjectForPath() method

Returns the project for which the specified path is underneath that project's folder. If the path is not under any project's folder, returns undefined.

<b>Signature:</b>

```typescript
tryGetProjectForPath(currentFolderPath: string): RushConfigurationProject | undefined;
```

## Parameters

|  <p>Parameter</p> | <p>Type</p> | <p>Description</p> |
|  --- | --- | --- |
|  <p>currentFolderPath</p> | <p>`string`</p> |  |

<b>Returns:</b>

`RushConfigurationProject | undefined`
