# `present.nvim`

Hey, this is a plugin for presenting markdown files.

# Features: Neovim Lua Execution
Can execute code in lua blocks, when you have them in a slide

```lua
print("Hello world", 37)
```
# Features: Other Langs

Can execute code in Language blocks, when you have them in a slide.

You may need to configure this with `opts.exectuors`, only have Python and Javascript by default.

```python
print("yaya python")
```

# Usage

```lua
require ("present").start_presentation {}
```

Use `n` and `p` to navigate markdown slides

Or use `:PresentStart` Command

# Credits

teej_dv
