# 1-crea tus primeras paginas web

Here you'll find how is it work with HTML and CSS with the objective to create a functional website.

### HTML
some concepts:

- `<fileset>`: To say that some fields are related.
    `<legend>`: Kind of text, or title of fileset

- `<label for="text">text</label>`: put text on the screen
textarea: make a box wich size is variable with a size by default. It takes taxt as a normal input 
```html
<textarea cols="70" rows="10"></textarea>
```

types:
- `text`: any kind of string.
- `email`: to say that need to have @ on the text.
- `tel`: to say is numeric information.
- `radio`: display options to choose.
- `checkbox`: little box allowed to check. <!--duh-->
- `submit`: to load its values.


properties:
`checked`: set by default to checked.
`required`: makes obligatory a field.

table:
- `<table></table>` to define a table wich has inside
    - `<thead></thead>`: title of table
        - `<th></th>`: cells of thead
    - `<tr></tr>` that means table row and
        - `<td></td>`: all cells of a row
    - `<tbody></tbody>`: body of table
        - `<th></th>`: cells of tbody

`<iframe src="url"></iframe>`: Allows us to create any kind of object in a box


### CSS:

- `cursor`: kind of cursor we like, pointer means to hand
- `transition`: transition to an animation
- `border-radius`: round border
- `border`: border of element
- `display`: way to show in screen
    - `display: block`: fills all the way
    - `display: inline`: only takes what it takes
    - `display: inline-block`: mix of both, all the way of what it takes
- `text-transform`: put takes how we likes
- `text-decoration`: if it got a link, how we see it

selector:
- `main > p{}`: will take only first line in hierarchy.
- `img + p {}`: will take the first paragraph after an image.
- `img ~ p {}`: will take same line in hierarchy as img.
- `main p:not(#id)`: will take all paragraph except one given

