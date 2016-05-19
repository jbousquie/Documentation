---
ID_PAGE: 25309
PG_TITLE: BinaryFileAssetTask
PG_VERSION: 2.1
---
## Description

class [BinaryFileAssetTask](/classes/2.4/BinaryFileAssetTask)

Load task on the given binary file

## Constructor

## new [BinaryFileAssetTask](/classes/2.4/BinaryFileAssetTask)(name, url)

The [BinaryFileAssetTask](/classes/2.4/BinaryFileAssetTask)

#### Parameters
 | Name | Type | Description
---|---|---|---
 | name | string |    The name
 | url | string |    The url for this binary file
## Members

### name : string

The name

### url : string

The url for this binary file

### onSuccess : (task: IAssetTask) =&gt; void

Function call when the mesh is load successfully

### onError : (task: IAssetTask) =&gt; void

Function call when the mesh isn't load successfully

### isCompleted : boolean

True if is completed, false otherwise.

### data : ArrayBuffer

The data

## Methods

### runundefined &rarr; void



#### Parameters
 | Name | Type | Description
---|---|---|---
undefined