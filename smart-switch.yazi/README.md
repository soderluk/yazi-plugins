# Smart switch: create tab if the tab being switched to does not exist

This plugin is from
[Yazi Tips: Smart switch: create tab if the tab being switched to does not exist](https://yazi-rs.github.io/docs/tips#smart-switch)

Bind the `2` key in your `keymap.toml`:

```toml
[[manager.prepend_keymap]]
on   = "2"
run  = "plugin smart-switch 1"
desc = "Switch or create tab 2"
```
