# Smart paste: `paste` files without entering the directory

This plugin is from
[Yazi Tips: Smart paste: paste files without entering the directory](https://yazi-rs.github.io/docs/tips#smart-paste)

Bind the `p` key in your `keymap.toml`:

```toml
[[manager.prepend_keymap]]
on   = "p"
run  = "plugin smart-paste"
desc = "Paste into the hovered directory or CWD"
```
