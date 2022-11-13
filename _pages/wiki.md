# wiki

::: warning
This feature is supported by macOS/iOS app only. The support of web edition is WIP.
:::
MarkNotes supports wiki links. Sample:

## Basic usage
### Input
```markdown
Click [[Markdown Quick Reference]] to learn markdown syntax
```

### Output
Click [[Markdown Quick Reference]] to learn markdown syntax


## In-page link
```
[[#header name]]
```
or if you want to show alternative text
```
[[#header name| text to show]]
```

## Cross-page link
### Link to a header of another note 
```markdown 
[[page title#header name]]
```
or 
```markdown 
[[page title#header name | text]]
```

Note:
- Don't include `#` in either title or header name;
- Page title is case sensitive, but header name will be case insensitive;

## Link to any part of another note 
Define an anchor in the target note:
```html
<a name="target"/>
```
Refer to the anchor:
```
[[page title#target | text]]
```
or
```
[[page title#target | text]]
```
