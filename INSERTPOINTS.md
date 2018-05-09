## Usage

### Include: Page

``` hbs
{{! @INSERT :: START @id: quote, @tag: component-partial }}
{{#with quote-bp.variations.simple}}
	{{> quote }}
{{/with}}

{{#with quote.variations.full}}
	{{> quote }}
{{/with}}
{{! @INSERT :: END }}
```
