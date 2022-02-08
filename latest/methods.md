# Methods
Methods, like variables, are not static, so you also need a vector instance to call them.

---

## Installed

The methods below set some value to the vector instance and return `undefined`

---

### `Vector2.set(x, y)`  

*Returns:* (`undefined`)

Sets two vector variables, more simply analog `Vector2.dir_set`

### `Vector2.set(vector)`  

*Returns:* (`undefined`)

The same notation as above, but receives one vector as input


---

### `Vector2.add(x, y)`  

*Returns:* (`undefined`)

### `Vector2.add(vector)`  

*Returns:* (`undefined`)

Adds the value of the argument to the current vector

---

### `Vector2.multi(x, y)`  

*Returns:* (`undefined`)

### `Vector2.multi(vector)`  

*Returns:* (`undefined`)

Multiplies the current vector by the value of the arguments, also has a complex counterpart in the form `Vector2.dir_multy`

---

### `Vector2.negative()`

*Returns:* (`undefined`)

Makes both vector coordinates negative

### `Vector2.zero()`

*Returns:* (`undefined`)

Sets the value of the vector to zero

## Installed Dir

Works like their simple counterparts, but uses [`vector2_dir`](variables#vector2_dir) to set the value

---

### `Vector2.dir_set(dir, value)`  

*Returns:* (`undefined`)

Sets vector values based on direction

---

### `Vector2.dir_add(dir, value)`  

*Returns:* (`undefined`)

Adds vector values based on direction

---

### `Vector2.dir_multi(dir, value)`  

*Returns:* (`undefined`)

Multiplies vector values depending on direction

---

## Returns

These methods do not affect the values of the vectors and have the result

---

### `Vector2.to_string([delimiter = ":"])`

*Returns:* (`string`)

Returns the values of the vector as a string (`x + delimiter + y`), separating them `delimiter`, delimiter is optional and defaults to `:`

---

### `Vector2._length()`

*Returns:* (`real`)

Returns the length of a vector according to the formula `sqr(x * x + y * y)`

---

### `Vector2._min(x, y)`

*Returns:* (`Vecotr2`)

### `Vector2._min(vector)`

*Returns:* (`Vecotr2`)

Returns the minimum value between itself and the argument

---

### `Vector2._max(x, y)`

*Returns:* (`Vecotr2`)

### `Vector2._max(vector)`

*Returns:* (`Vecotr2`)

Returns the maximum value between itself and the argument


---

### `Vector2._clamp(min_x, min_y, max_x, max_y)`

*Returns:* (`Vecotr2`)

### `Vector2._clamp(min_vector, max_vector)`

*Returns:* (`Vecotr2`)

Limits value on both sides

---

### `Vector2._lerp(x, y, [amount = 0.5])`

*Returns:* (`Vecotr2`)

### `Vector2._lerp(vector, [amount = 0.5])`

*Returns:* (`Vecotr2`)

Works the same as Lera, but for both coordinates see [Docmentation](https://manual.yoyogames.com/GameMaker_Language/GML_Reference/Maths_And_Numbers/Number_Functions/lerp.htm)