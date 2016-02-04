# Quote

This component is based on the blueprint of Veams-Components.

## Usage

### Include: Page

``` hbs
{{! @INSERT :: START @id: quote, @tag: component }}
{{#with quote-bp.simple}}
	{{> c-quote }}
{{/with}}

{{#with quote-bp.full}}
	{{> c-quote }}
{{/with}}
{{! @INSERT :: END }}
```

### Include: SCSS

``` scss
// @INSERT :: START @id: scss-import, @tag: component
@import "components/_c-quote";
// @INSERT :: END
```
