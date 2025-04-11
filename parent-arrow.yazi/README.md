# Navigation in the parent directory without leaving the CWD

This plugin is from
[Yazi Tips: Navigation in the parent directory without leaving the CWD](https://yazi-rs.github.io/docs/tips#parent-arrow)

Bind the `K` and `J` keys in your `keymap.toml`:

```toml
[[manager.prepend_keymap]]
on = "k"
run = "plugin parent-arrow -1"

[[manager.prepend_keymap]]
on = "j"
run = "plugin parent-arrow 1"
```
