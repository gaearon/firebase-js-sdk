{% extends "_internal/templates/reference.html" %}
{% block title %}Title{% endblock title %}
{% block body %}

## SettableMetadata interface

Object metadata that can be set at any time.

<b>Signature:</b>

```typescript
export interface SettableMetadata 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [cacheControl](./storage-types.settablemetadata.md#settablemetadatacachecontrol_property) | string \| undefined | Served as the 'Cache-Control' header on object download. |
|  [contentDisposition](./storage-types.settablemetadata.md#settablemetadatacontentdisposition_property) | string \| undefined | Served as the 'Content-Disposition' header on object download. |
|  [contentEncoding](./storage-types.settablemetadata.md#settablemetadatacontentencoding_property) | string \| undefined | Served as the 'Content-Encoding' header on object download. |
|  [contentLanguage](./storage-types.settablemetadata.md#settablemetadatacontentlanguage_property) | string \| undefined | Served as the 'Content-Language' header on object download. |
|  [contentType](./storage-types.settablemetadata.md#settablemetadatacontenttype_property) | string \| undefined | Served as the 'Content-Type' header on object download. |
|  [customMetadata](./storage-types.settablemetadata.md#settablemetadatacustommetadata_property) | \| { \[key: string\]: string; } \| undefined | Additional user-defined custom metadata. |

## SettableMetadata.cacheControl property

Served as the 'Cache-Control' header on object download.

<b>Signature:</b>

```typescript
cacheControl?: string | undefined;
```

## SettableMetadata.contentDisposition property

Served as the 'Content-Disposition' header on object download.

<b>Signature:</b>

```typescript
contentDisposition?: string | undefined;
```

## SettableMetadata.contentEncoding property

Served as the 'Content-Encoding' header on object download.

<b>Signature:</b>

```typescript
contentEncoding?: string | undefined;
```

## SettableMetadata.contentLanguage property

Served as the 'Content-Language' header on object download.

<b>Signature:</b>

```typescript
contentLanguage?: string | undefined;
```

## SettableMetadata.contentType property

Served as the 'Content-Type' header on object download.

<b>Signature:</b>

```typescript
contentType?: string | undefined;
```

## SettableMetadata.customMetadata property

Additional user-defined custom metadata.

<b>Signature:</b>

```typescript
customMetadata?:
    | {
        [key: string]: string;
      }
    | undefined;
```
{% endblock body %}