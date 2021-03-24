## **CSS name conventions**  📖
### `--clr` 👉 _color_

- _primary -_ **200** 👈 as bigger the number gets, the colors is becoming darker
&nbsp;
> _example_ 👉 `--clr-primary-200: #f3eed9;`

> _example_ 👉 `--clr-neutral-900: #222c2a;`
&nbsp;

### `--ff` 👉 _font family_
&nbsp;
### `--primary`👉 used in most places
&nbsp;
### `--accent`👉 to add some flare to a specific place

```
/*example:*/
  --ff-primary: 'Roboto', sans-serif;
  --ff-accent: 'Playfair Display', serif;
```
&nbsp;
### `bg` 👉 _background_
&nbsp;
### `--`👉 _modification on original values_(we are using **container** defaults but we are adding some additional values with **container--narrow**)
> `example 👉 <div class="container container--narrow">`

>` container--narrow`
&nbsp;
```
  /*every element that has a sibling before it*/

  .split > * + *{
    margin-left: 2em;
  }
```
***