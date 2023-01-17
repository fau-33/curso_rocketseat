## border (e outline)

As bordas da caixa

- value: `<border-style` | `<border-width` | `<border-color>`
  - style: solid | dotted | dashed | double | groove | ridge | inset | outset
  - width: `<length`
  - color: `<color>`

```css
div {
  /* shorthand */
  border-top: solid 2px; /* top | bottom | right | left */

  /* style */
  border: solid;

  /* width <length> | style */
  border: 2px dotted;

  /* style | color */
  border: outset #f33;

  /* width | style | color */
  border: medium dashed green;
}
```

### E outline?

- difere em quatros sentidos
  - Não modifica o valor da caixa, pois não é parte do Box model
  - Poderá ser diferente de retangular
  - Não permite ajuste individuais
  - Mais usado pelo user agent para acessibilidade 
