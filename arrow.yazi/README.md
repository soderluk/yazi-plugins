# File navigation wraparound

This plugin is from
[Yazi Tips: File navigation wraparound](https://yazi-rs.github.io/docs/tips#navigation-wraparound)

Bind the `k` and `j` keys in your `keymap.toml`:

```toml
[[manager.prepend_keymap]]
on = "k"
run = "plugin arrow -1"

[[manager.prepend_keymap]]
on = "j"
run = "plugin arrow 1"
```
