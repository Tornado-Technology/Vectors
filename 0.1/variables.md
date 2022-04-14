# Variables

---

### vector2_dir
enum for [Vector2 dir](methods#installed-dir) methods
I try made a system similar to the one that is now in [Unity](https://docs.unity3d.com/ScriptReference/Vector2.html)

The daw parameter in these methods is responsible for where the value will be set.
An entry like `Vector2(-1, 0)` means that the value is set only `x` and will be negative

For example, merhod `Vector2.dir_set(10, vector2_dir.down)` will set the values of the vector `y` to `-10`

| Key  | Value | Direction       |
|------|-------|-----------------|
|down  |   0   | Vector2(0, -1)  |
|left  |   1   | Vector2(-1, 0)  |
|one   |   2   | Vector2(1,  1)  |
|right |   3   | Vector2(1,  0)  |
|up    |   4   | Vector2(0,  1)  |
|negone|   5   | Vector2(-1, -1) |
