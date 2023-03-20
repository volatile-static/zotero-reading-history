<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [zotero-plugin-toolkit](./zotero-plugin-toolkit.md) &gt; [ItemBoxManager](./zotero-plugin-toolkit.itemboxmanager.md) &gt; [unregister](./zotero-plugin-toolkit.itemboxmanager.unregister.md)

## ItemBoxManager.unregister() method

Unregister a row of specific field.

<b>Signature:</b>

```typescript
unregister(field: string, options?: {
        skipIsFieldOfBase?: boolean;
        skipGetField?: boolean;
        skipSetField?: boolean;
        skipRefresh?: boolean;
    }): void;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  field | string |  |
|  options | { skipIsFieldOfBase?: boolean; skipGetField?: boolean; skipSetField?: boolean; skipRefresh?: boolean; } | <i>(Optional)</i> Skip unregister of certain hooks. This is useful when the hook is not initialized by this instance |

<b>Returns:</b>

void
