{% extends "_internal/templates/reference.html" %}
{% block title %}Title{% endblock title %}
{% block body %}

## LoadBundleTaskProgress interface

Represents a progress update or a final state from loading bundles.

<b>Signature:</b>

```typescript
export declare interface LoadBundleTaskProgress 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [bytesLoaded](./firestore_.loadbundletaskprogress.md#loadbundletaskprogressbytesloaded_property) | number | How many bytes have been loaded. |
|  [documentsLoaded](./firestore_.loadbundletaskprogress.md#loadbundletaskprogressdocumentsloaded_property) | number | How many documents have been loaded. |
|  [taskState](./firestore_.loadbundletaskprogress.md#loadbundletaskprogresstaskstate_property) | [TaskState](./firestore_.md#taskstate_type) | Current task state. |
|  [totalBytes](./firestore_.loadbundletaskprogress.md#loadbundletaskprogresstotalbytes_property) | number | How many bytes are in the bundle being loaded. |
|  [totalDocuments](./firestore_.loadbundletaskprogress.md#loadbundletaskprogresstotaldocuments_property) | number | How many documents are in the bundle being loaded. |

## LoadBundleTaskProgress.bytesLoaded property

How many bytes have been loaded.

<b>Signature:</b>

```typescript
bytesLoaded: number;
```

## LoadBundleTaskProgress.documentsLoaded property

How many documents have been loaded.

<b>Signature:</b>

```typescript
documentsLoaded: number;
```

## LoadBundleTaskProgress.taskState property

Current task state.

<b>Signature:</b>

```typescript
taskState: TaskState;
```

## LoadBundleTaskProgress.totalBytes property

How many bytes are in the bundle being loaded.

<b>Signature:</b>

```typescript
totalBytes: number;
```

## LoadBundleTaskProgress.totalDocuments property

How many documents are in the bundle being loaded.

<b>Signature:</b>

```typescript
totalDocuments: number;
```
{% endblock body %}