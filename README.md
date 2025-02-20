All credit for the code in this repo goes to the author of modus-themes.nvim. I'm just changing a couple colors to make things show up better on my Dasung color e-ink monitor. I imagine what's left is hardly what the Modus author had in mind, it just happened to work well as a jumping off point.

# Install with Lazy.nvim

```lua
require("lazy").setup({
{ "saltzm/modus-themes-eink.nvim" },
....
})

vim.cmd [[colorscheme modus_operandi]]
```
