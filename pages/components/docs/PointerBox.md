# PointerBox

## Default example

```.jsx
<PointerBox m={4} p={2} minHeight={100} bg="green.1" borderColor="green.5">
  PointerBox
</PointerBox>
```

## System props

PointerBox components get `LAYOUT` and `COMMON` system props. Read our [System Props](/system-props) doc page for a full list of available props.

## Component props

| Prop name | Type | Description |
| :- | :- | :- |
| caret | String | Sets the location of the caret. The format is `[edge]-[position on edge]`. For example, `right-top` will position the caret on the top of the right edge of the box. Use `top`, `right`, `bottom`, or `left` to position a caret in the center of that edge. |

export const meta = {displayName: 'PointerBox'}