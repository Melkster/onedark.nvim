# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [unreleased]

### Added

- docs updated
- Assign `dark5` color to `LineNr` inside `transparent` mode
- docs: contributing guidelines added
- docs: code of conduct added
- feat: `highlight_linenumber` config for setting dark color to number line
- feat: support `highlight_linenumber` with gitsigns
- enhance: nvim-cmp highlight
- change popup 'select' highlight background to green
- enhance(nvim-cmp):separate match highlights
- plugin-support: [nvim-notify](https://github.com/rcarriga/nvim-notify)
- enhance: set default config value to `vim.g` variables
- feat: `onedark_transparent_sidebar` option #60
- docs: vim config docs added inside README.md
- feat: store `user_config` value to `vim.g` variables
- docs: luadoc added inside `config` and `extra` module
- A new lualine theme added 'onedark-nvim' #65
- expose onedark theme in [fzf.vim](https://github.com/junegunn/fzf.vim)
- added hot reloaded to `onedark-nvim` lualine theme
- feat: `lualine_bold` option added
- luadoc: fix warning inside config module
- fixed #71 in normal mode

### Changed

- projekt0n/github-nvim-theme#73 fixed
- refactor: lualine colors added inside `colors.lua`
- breaking change: consistent variable naming in `onedark` config
- undefined color `syntax.comment` fixed
- lualine theme provided by official lualine repo (fix #46)
- refactor: group colors according to assignment
- enhance: barbar highlighting monsonjeremy/onedark.nvim#16
- enhance: 'cmp' menu with 'fg' color
- docs: minimal screenshot updated in [README.md#minimal](https://github.com/ful1e5/onedark.nvim#minimal)
- docs: removed emoji from README.md
- cleanup: removed vim config deprecated message
- breaking change: use snake_case inside config and alacritty module
- breaking change: changed config variables name inside `vim.g` variables
- refactor: colors transform config inside `extra` module
- fix: diff text with comment text #68
- docs: cleanup some nonsense

## [v0.0.2]- 19 Sep 2021

### Added

- **Warning** on `vim.g` configuration
- Configure plugin in lua using `require('onedark').setup({})` **[fix monsonjeremy/onedark.nvim#5]**
- Minimal config example added inside [README.md#minimal](./README.md#minimal)
- Linting Github Action init
- Format .lua code with [lua-format](https://github.com/Koihik/LuaFormatter)
- **kitty tab** colors are changed
- Init: `Makefile, .lua-format, .luacheckrc`
- Add "NONE" color compatibility for colors override
- `barbar.nvim` plugin support. related to monsonjeremy/onedark.nvim#8
- `glyph-palette.vim` plugin support
- kitty border color added
- `./colors/onedark.vim` code in lua
- [nvim-web-devicons](https://github.com/kyazdani42/nvim-web-devicons) plugin support
- `msg_area_style` config added
- `kitty` target added inside `Makefile` for reloading kitty theme
- `TSVariable` & `TSOperator` colors added inside `colors.lua`
- `cursor`, `TSProperty`, `jsonTSLabel`, `lessInclude`, `lessClass`, `cssStringQQ`, `makeIdent` colors added
- php, javascript, python, ruby, scss, bash , typescript, sql, xml, yaml syntax highlighting improved
- refactor: colors file to `lua`

### Changed

- Removed function `require('onedark').colorscheme()`
- Colorscheme **autoload removed** from `colors/onedark.vim`
- **VertSplit** & **Inactive StatusLine** `fg` color changed to `bg_visual`
- StatusLine bug note inside [README.md#usage](./README.md#-usage)
- Configuration docs updated inside [README.md#configuration](./README.md#-configuration)
- Fix `VertSplit` & `StatusLine` crossover on `hide_inactive_statusline` [check hoob3rt/lualine.nvim#274]
- Parse lua table inside `colors` config **[fix #6]**
- Better Telescope highlighting
- Removed `_` from extra themes name
- inactive statusline background color

## [v0.0.1] - 14 June 2021

### Added

- Initial release 🎊

[unreleased]: https://github.com/ful1e5/onedark.nvim/compare/v0.0.2...main
[v0.0.2]: https://github.com/ful1e5/onedark.nvim/compare/v0.0.2...v0.0.1
[v0.0.1]: https://github.com/ful1e5/onedark.nvim/tree/v0.0.1
