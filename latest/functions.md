# Functions

---

## Converts

---

### `vector2_to_string(Vector2, [delimiter = ":"])`

_Returns:_ (`string`)

Did the same thing as `Vector2.to_string`, but in a different wrapper

---

## Display

Some methods work with `display_gui`

---

### `display_get_gui_size()`

_Returns:_ (`Vector2`)

Return `display_get_gui_width()` & `display_get_gui_height()` wraped to `Vector2`

---

### `display_set_gui_vsize()`

_Returns:_ (`undefined`)

Set display size to `Vector2`

---

## Position

Some functions for working with object position

---

### `position_get([object = id])`

_Returns:_ (`Vector2`)

Returns `Vector2` with `x = object.x, y = object.y`

---

### `position_set(Vector2, [object = id])`

_Returns:_ (`undefined`)

Set object `x, y` to `Vector2.x, Vector2.y`

---

### `position_add(Vector2, [object = id])`

_Returns:_ (`undefined`)

Add object `x, y` to `Vector2.x, Vector2.y`

---

### `position_multi(Vector2, [object = id])`

_Returns:_ (`undefined`)

Multiply object `x, y` to `Vector2.x, Vector2.y`
