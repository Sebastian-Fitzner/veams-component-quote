<p align="right">
<a href="https://badge.fury.io/js/%40veams%2Fcomponent-quote"><img src="https://badge.fury.io/js/%40veams%2Fcomponent-quote.svg" alt="npm version" height="18"></a>
    <a href="https://gitter.im/Sebastian-Fitzner/Veams?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge"><img src="https://badges.gitter.im/Sebastian-Fitzner/Veams.svg" alt="Gitter Chat" /></a>
</p>

# Quote

## Description

A simple quote component. The specs says:

> The `<blockquote>` element represents a section that is quoted from another source.
Content inside a `<blockquote>` must be quoted from another source, whose address, if it has one, may be cited in the cite attribute

-----------

## Installation

### Installation with Veams

```bash
veams install component quote
```
``` bash 
veams -i c quote
```

-----------

## Fields

### `quote.hbs`

#### Settings

| Parameter | Type | Value | Description |
|:--- | :---: |:---: | :--- |
| settings.quoteContextClass | String | `default` | Context class of component. |
| settings.quoteClasses | String | | Modifier classes for component. |

#### Content

| Parameter | Type | Description |
|:--- | :---: | :--- |
| content.quoteContent | String | Content text in blockquote. |
| content.quoteAuthor | String | Author of quote. |
