# Methods

Methods, like variables, are not static, so you also need a vector instance to call them.

---

## Installed

The methods below set some value to the vector instance and return `undefined`

---

### `Vector2.set(x, y)`

_Returns:_ (`self`)

Sets two vector variables, more simply analog `Vector2.dir_set`

### `Vector2.set(Vector2)`

_Returns:_ (`self`)

The same notation as above, but receives one vector as input

---

### `Vector2.add(x, y)`

_Returns:_ (`self`)

### `Vector2.add(Vector2)`

_Returns:_ (`self`)

Adds the value of the argument to the current vector, also has a complex counterpart in the form `Vector2.dir_add`

---

### `Vector2.sub(x, y)`

_Returns:_ (`self`)

### `Vector2.sub(Vector2)`

_Returns:_ (`self`)

Subtracts the value of the argument to the current vector, so far it has no analogues in dir-methods

---

### `Vector2.multi(x, y)`

_Returns:_ (`self`)

### `Vector2.multi(Vector2)`

_Returns:_ (`self`)

Multiplies the current vector by the value of the arguments, also has a complex counterpart in the form `Vector2.dir_multy`

---

### `Vector2.divis(x, y)`

_Returns:_ (`self`)

### `Vector2.divis(Vector2)`

_Returns:_ (`self`)

Divides the current vector by the value of the arguments, so far it has no analogues in dir-methods

---

### `Vector2.one()`

_Returns:_ (`self`)

Makes both vector coordinates to one

### `Vector2.negative()`

_Returns:_ (`self`)

Makes both vector coordinates negative

### `Vector2.zero()`

_Returns:_ (`self`)

Sets the value of the vector to zero


## Converts

Methods to help represent a vector in a different way

---

### `Vector2.to_string([delimiter = ":"])`

_Returns:_ (`string`)

Returns the values of the vector as a string (`x + delimiter + y`), separating them `delimiter`, delimiter is optional and defaults to `:`

---

### `Vector2.to_array([mirror = false])`

_Returns:_ (`array`)

Returns an array with value `[x, y]` if parameter is `mirror = true` then `[y, x]`

---

### `Vector2.to_list([mirror = false])`

_Returns:_ (`ds_list`)

Returns an ds_list with value `[x, y]` if parameter is `mirror = true` then `[y, x]`

---

## Utils

Various useful compilation method

---

### `Vector2.copy()`

_Returns:_ (`Vector2`)

Returns a new `Vector2` with the same values (this can be useful since a struct is a data type reference)

---

## Math

### `Vector2.math_length()`

_Returns:_ (`real`)

Returns the length of a vector according to the formula `sqr(x * x + y * y)`

---

### `Vector2.math_min(x, y)`

_Returns:_ (`Vecotr2`)

### `Vector2.math_min(Vector2)`

_Returns:_ (`Vecotr2`)

Returns the minimum value between itself and the argument

---

### `Vector2.math_max(x, y)`

_Returns:_ (`Vecotr2`)

### `Vector2.math_max(Vector2)`

_Returns:_ (`Vecotr2`)

Returns the maximum value between itself and the argument

---

### `Vector2.math_clamp(min_x, min_y, max_x, max_y)`

_Returns:_ (`Vecotr2`)

### `Vector2.math_clamp(min_Vector2, max_Vector2)`

_Returns:_ (`Vecotr2`)

Limits value on both sides

---

### `Vector2.math_lerp(x, y, [amount = 0.5])`

_Returns:_ (`Vecotr2`)

### `Vector2.math_lerp(Vector2, [amount = 0.5])`

_Returns:_ (`Vecotr2`)

Works the same as Lerp, but for both coordinates see [Docmentation](https://manual.yoyogames.com/GameMaker_Language/GML_Reference/Maths_And_Numbers/Number_Functions/lerp.htm)

## Installed Dir

Works like their simple counterparts, but uses [`vector2_dir`](variables#vector2_dir) to set the value

---

### `Vector2.dir_set(dir, value)`

_Returns:_ (`undefined`)

Sets vector values based on direction

---

### `Vector2.dir_add(dir, value)`

_Returns:_ (`undefined`)

Adds vector values based on direction

---

### `Vector2.dir_multi(dir, value)`

_Returns:_ (`undefined`)

Multiplies vector values depending on direction

---
