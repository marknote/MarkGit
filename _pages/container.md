# container

Markdown container allows defining your own style for a custom block.

Sample:
## Input
```markdown
<style>
.warning {
    background-color: yellow;
}
</style>
::: warning
Some warning information
:::
```

## Output
::: warning
<style>
.warning {
    background-color: yellow;
}
</style>
Some warning information
:::

## Note
Mac and iOS edition supports defining global custom rendering style with CSS.