<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [zotero-plugin-toolkit](./zotero-plugin-toolkit.md) &gt; [PrefPaneOptions](./zotero-plugin-toolkit.prefpaneoptions.md)

## PrefPaneOptions interface

**Signature:**

```typescript
export interface PrefPaneOptions 
```

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [defaultXUL?](./zotero-plugin-toolkit.prefpaneoptions.defaultxul.md) |  | boolean | _(Optional)_  true |
|  [extraDTD?](./zotero-plugin-toolkit.prefpaneoptions.extradtd.md) |  | string\[\] | _(Optional)_ |
|  [helpURL?](./zotero-plugin-toolkit.prefpaneoptions.helpurl.md) |  | string\[\] | _(Optional)_ If provided, a help button will be displayed under the pane and the provided URL will open when it is clicked |
|  [id?](./zotero-plugin-toolkit.prefpaneoptions.id.md) |  | string | _(Optional)_ Represents the pane and must be unique. Automatically generated if not provided |
|  [image?](./zotero-plugin-toolkit.prefpaneoptions.image.md) |  | string | _(Optional)_ URI of an icon to be displayed in the navigation sidebar, optionally relative to the plugin's root. If not provided, the plugin's icon (from manifest.json) is used. |
|  [label?](./zotero-plugin-toolkit.prefpaneoptions.label.md) |  | string | _(Optional)_ Displayed as the pane's label in the sidebar. If not provided, the plugin's name is used. |
|  [onload?](./zotero-plugin-toolkit.prefpaneoptions.onload.md) |  | (win: Window) =&gt; any | _(Optional)_ |
|  [parent?](./zotero-plugin-toolkit.prefpaneoptions.parent.md) |  | string | _(Optional)_ ID of parent pane (if provided, pane is hidden from the sidebar) |
|  [pluginID](./zotero-plugin-toolkit.prefpaneoptions.pluginid.md) |  | string | ID of the plugin registering the pane |
|  [scripts?](./zotero-plugin-toolkit.prefpaneoptions.scripts.md) |  | string\[\] | _(Optional)_ Array of URIs of scripts to load along with the pane, optionally relative to the plugin's root |
|  [src](./zotero-plugin-toolkit.prefpaneoptions.src.md) |  | string | URI of an XHTML fragment, optionally relative to the plugin's root |
|  [stylesheets?](./zotero-plugin-toolkit.prefpaneoptions.stylesheets.md) |  | string\[\] | _(Optional)_ Array of URIs of CSS stylesheets to load along with the pane, optionally relative to the plugin's root  Zotero 7 |
