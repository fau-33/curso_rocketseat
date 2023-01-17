## margin

Espaços entre os elementos

- margin-top | margin-bottom | margin-left | margin-right
- values: `<length` | `<porcentage>` | auto

```css
div {
  /* shorthand */
  margin: 12px 16px 10px 4px;
  margin: 12px 16px 0;
  margin: 8px 16px;
  margin: 8px;
}
```

  *Cuidado com a margin collapsing (top se ajusta ao bottom)