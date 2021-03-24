## **CSS name conventions**

### `--clr` 👉 _color_

- _primary -_ **200** 👈 as bigger the number gets, the colors is becoming darker

> _example:_ `--clr-primary-200: #f3eed9;`

> _example:_ `--clr-neutral-900: #222c2a;`

### `--ff` 👉 _font family_

### `--primary`👉 used in most places

### `--accent`👉 to add some flare to a specific place

```
#example:
  --ff-primary: 'Roboto', sans-serif;
  --ff-accent: 'Playfair Display', serif;
```

### `bg` 👉 _background_

### `--`👉 _modification on original values_(we are using **container** defaults but we are adding some additional values with **container--narrow**)
> _example:_  `<div class="container container--narrow">`

>` container--narrow`

_every element that has a sibling before it_
```
  .split > * + *{
    margin-left: 2em;
  }
```