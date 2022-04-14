# Methods

Methods, like variables, are not static, so you also need a vector instance to call them.

---

## Installed

The methods below set some value to the vector instance and return `undefined`

---

### `set(x, y)`

_Returns:_ (`self`)

Sets two vector variables, more simply analog `Vector2.dir_set`

### `set(Vector2)`

_Returns:_ (`self`)

The same notation as above, but receives one vector as input

---

### `add(x, y)`

_Returns:_ (`self`)

### `add(Vector2)`

_Returns:_ (`self`)

Adds the value of the argument to the current vector, also has a complex counterpart in the form `Vector2.dir_add`

---

### `sub(x, y)`

_Returns:_ (`self`)

### `sub(Vector2)`

_Returns:_ (`self`)

Subtracts the value of the argument to the current vector, so far it has no analogues in dir-methods

---

### `multi(x, y)`

_Returns:_ (`self`)

### `multi(Vector2)`

_Returns:_ (`self`)

Multiplies the current vector by the value of the arguments, also has a complex counterpart in the form `Vector2.dir_multy`

---

### `divis(x, y)`

_Returns:_ (`self`)

### `divis(Vector2)`

_Returns:_ (`self`)

Divides the current vector by the value of the arguments, so far it has no analogues in dir-methods

---

### `one()`

_Returns:_ (`self`)

Makes both vector coordinates to one

### `negative()`

_Returns:_ (`self`)

Makes both vector coordinates negative

### `zero()`

_Returns:_ (`self`)

Sets the value of the vector to zero

## Converts

Methods to help represent a vector in a different way

---

### `to_string([delimiter = ":"])`

_Returns:_ (`string`)

Returns the values of the vector as a string (`x + delimiter + y`), separating them `delimiter`, delimiter is optional and defaults to `:`

---

### `to_array([mirror = false])`

_Returns:_ (`array`)

Returns an array with value `[x, y]` if parameter is `mirror = true` then `[y, x]`

---

### `to_list([mirror = false])`

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

### `math_distance_to(Vector2)`

_Returns:_ (`real`)

Returns the distance between itself and another vector

---

### `math_dot(Vector2)`

_Returns:_ (`real`)

Returns the scalar product between itself and another vector

---

### `math_cross(Vector2)`

_Returns:_ (`real`)

Returns the cross product between itself and another vector

---

### `math_angle(radians)`

_Returns:_ (`real`)

Returns angle with respect to the `x` axis itself. The `radians` argument is responsible for the result returned, if it is true it will return the angle in **radians** otherwise **degree**

---

### `math_sign()`

_Returns:_ (`Vector2`)

Returns a new Vector2 with all components in `sign` values

---

### `math_signv()`

_Returns:_ (`self`)

Sets itslef components in `sign` values

---

### `math_abs()`

_Returns:_ (`Vector2`)

Returns a new Vector2 with all components in `abs` values

---

### `math_absv()`

_Returns:_ (`Vector2`)

Sets itslef components in `abs` values

---

### `math_power(n)`

_Returns:_ (`Vector2`)

Returns a new Vector2 with all components multiplied by all components of Vector2 `n`

---

### `math_powerv(n)`

_Returns:_ (`Vector2`)

Sets itslef components in multiplied by all components of Vector2 `n`

---

### `math_round()`

_Returns:_ (`self`)

Sets itslef components in `round` values

---

### `math_ceil()`

_Returns:_ (`Vector2`)

Sets itslef components in `ceil` values

---

### `math_floor()`

_Returns:_ (`self`)

Sets itslef components in `floor` values

---

### `Vector2.math_length()`

_Returns:_ (`real`)

Returns the length of a vector according to the formula `sqr(x * x + y * y)`

---

### `Vector2.math_min(Vector2)`

_Returns:_ (`Vecotr2`)

Returns the minimum value between itself and the argument

---

### `Vector2.math_minv(Vector2)`

_Returns:_ (`self`)

Sets itslef components minimum value between itself and the argument

---

### `Vector2.math_max(Vector2)`

_Returns:_ (`Vecotr2`)

Returns the maximum value between itself and the argument

---

### `Vector2.math_maxv(Vector2)`

_Returns:_ (`self`)

Sets itslef components maximum value between itself and the argument

---

### `Vector2.math_clamp(minVector2, maxVector2)`

_Returns:_ (`Vecotr2`)

Returns a new Vector2 with all components limits value on both sides

---

### `Vector2.math_clampv(minVector2, maxVector2)`

_Returns:_ (`self`)

Sets itslef components limits value on both sides

---

### `Vector2.math_lerp(targetVector2, amountVector2)`

_Returns:_ (`Vecotr2`)

Works the same as Lerp, but for both coordinates see [Docmentation](https://manual.yoyogames.com/GameMaker_Language/GML_Reference/Maths_And_Numbers/Number_Functions/lerp.htm)

### `Vector2.math_lerpv(targetVector2, amountVector2)`

_Returns:_ (`Vecotr2`)

Returns a new Vector2 with all components lerped. Works the same as Lerp, but for both coordinates see [Docmentation](https://manual.yoyogames.com/GameMaker_Language/GML_Reference/Maths_And_Numbers/Number_Functions/lerp.htm)

## Installed Dir

Sets itslef components with all components lerped

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
