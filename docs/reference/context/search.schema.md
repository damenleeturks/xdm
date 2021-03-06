
# Search Schema

```
https://ns.adobe.com/xdm/context/search
```

Information about web search activity.

| [Abstract](../../abstract.md) | [Extensible](../../extensions.md) | [Status](../../status.md) | [Identifiable](../../id.md) | [Custom Properties](../../extensions.md) | [Additional Properties](../../extensions.md) | Defined In |
|-------------------------------|-----------------------------------|---------------------------|-----------------------------|------------------------------------------|----------------------------------------------|------------|
| Can be instantiated | Yes | Stabilizing | No | Forbidden | Permitted | [context/search.schema.json](context/search.schema.json) |

## Search Example
```json
{
  "xdm:searchEngine": "Google",
  "xdm:keywords": "rice cooker",
  "xdm:isPaid": true,
  "xdm:pageDepth": 1
}
```

# Search Properties

| Property | Type | Required | Defined by |
|----------|------|----------|------------|
| [xdm:isPaid](#xdmispaid) | `boolean` | Optional | Search (this schema) |
| [xdm:keywords](#xdmkeywords) | `string` | Optional | Search (this schema) |
| [xdm:pageDepth](#xdmpagedepth) | `integer` | Optional | Search (this schema) |
| [xdm:searchEngine](#xdmsearchengine) | `string` | Optional | Search (this schema) |
| `*` | any | Additional | this schema *allows* additional properties |

## xdm:isPaid
### Is Paid

Indicate if the search is paid or not.

`xdm:isPaid`
* is optional
* type: `boolean`
* defined in this schema

### xdm:isPaid Type


`boolean`





## xdm:keywords
### Keywords

The keywords for the search.

`xdm:keywords`
* is optional
* type: `string`
* defined in this schema

### xdm:keywords Type


`string`






## xdm:pageDepth
### Page Depth

The page depth in the search results.

`xdm:pageDepth`
* is optional
* type: `integer`
* defined in this schema

### xdm:pageDepth Type


`integer`






## xdm:searchEngine
### Search Engine

The search engine used by the search.

`xdm:searchEngine`
* is optional
* type: `string`
* defined in this schema

### xdm:searchEngine Type


`string`





