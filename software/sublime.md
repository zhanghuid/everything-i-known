## 下载地址
```
https://www.sublimetext.com/
```

## 配置文件
1. sublime-keymap
```json
[
    { "keys": ["super+]"], "command": "goto_definition" },
    { "keys": ["super+["], "command": "jump_back" },
    { "keys": ["ctrl+shift+o"], "command": "open_recent_file"},

]

```

2. sublime-settings
```json
{
	"bootstrapped": true,
	"in_process_packages":
	[
	],
	"installed_packages":
	[
		"A File Icon",
		"AdvancedNewFile",
		"Anaconda",
		"anaconda_go",
		"anaconda_php",
		"BracketHighlighter",
		"DocBlockr",
		"EditorConfig",
		"Laravel Blade Highlighter",
		"LSP",
		"LSP-intelephense",
		"Material Theme",
		"Package Control",
		"PackageResourceViewer",
		"PHP Companion",
		"PHP Completions Kit",
		"SublimeLinter",
		"SublimeLinter-php",
		"Sync Settings",
		"Vue Syntax Highlight",
	],
}

```

3. Preferences.sublime-settings
```
// Settings in here override those in "Default/Preferences.sublime-settings",
// and are overridden in turn by syntax-specific settings.
{
	"args":
    {
        "target": "browser",
    },
    "bold_folder_labels": true,
    "caret_style": "phase",
    "ensure_newline_at_eof_on_save": true,
    "find_selected_text": true,
    "findreplace_small": true,
    "folder_exclude_patterns":
    [
        ".svn",
        ".git",
        ".hg",
        "CVS",
        "node_modules",
        "bower_components"
    ],
    "font_face": "JetBrains Mono",
    "font_size": 14,
    "highlight_line": true,
    "hot_exit": false,
    "ignored_packages":
    [
        "Vintage",
    ],
    "keys":
    [
        "alt+m"
    ],
    "line_numbers": true,
    "line_padding_bottom": 4,
    "line_padding_top": 4,
    "material_theme_accent_blue": true,
    "material_theme_accent_sky": true,
    "material_theme_big_fileicons": true,
    "material_theme_bold_tab": true,
    "material_theme_tree_headings": true,
    "material_theme_bullet_tree_indicator": true,
    "material_theme_compact_sidebar": true,
    "material_theme_small_tab": true,
    "material_theme_tabs_autowidth": true,
    "open_files_in_new_window": true,
    "overlay_scroll_bars": true,
    "parameters":
    [
        "/START",
        "%CWD%"
    ],
    "rulers":
    [
        80
    ],
    "show_definitions": false,
    "show_encoding": true,
    "spell_check": false,
    "tab_size": 4,
    "tabs_medium": true,
    "tabs_small": false,
    "theme": "Material-Theme.sublime-theme",
    "translate_tabs_to_spaces": true,
    "trim_trailing_white_space_on_save": true,
    "ui_big_tabs": true,
    "ui_sidebar_highlight_row": true,
    "update_check": false,
    "use_simple_full_screen": true,
    "word_wrap": false,
    "color_scheme": "Packages/Material Theme/schemes/Material-Theme.tmTheme",
    "material_theme_titlebar": true,
}

```