<div align="center">
<h1>My Neovim Plugin Template</h1>
<p align="center">
<a href="https://github.com/realShaneYost/nvim-skel.nvim/actions/workflows/ci.yaml">
<img src="https://github.com/realShaneYost/nvim-skel.nvim/actions/workflows/ci.yaml/badge.svg" alt="CI Status">
</a>
<a href="https://github.com/realShaneYost/nvim-skel.nvim/blob/main/LICENSE">
<img src="https://img.shields.io/github/license/realShaneYost/nvim-skel.nvim" alt="License">
</a>
<a href="https://github.com/realShaneYost/nvim-skel.nvim/issues">
<img src="https://img.shields.io/github/issues/realShaneYost/nvim-skel.nvim" alt="GitHub Issues">
</a>
</p>
</div>

## About
A quick and simple starter template for kicking off a neovim plugin project.

## Configuration

```lua
return {
    "realShaneYost/nvim-skel.nvim",
    -- dir = "~/repos/nvim-skel.nvim",
    -- dev = true,
    dependencies = { "nvim-lua/plenary.nvim" },
    config = function()
        local tablegen = require("nvim-skel")
        tablegen.setup({
        })
    end,
}
```
