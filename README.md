# Godot Project Starter

A simple strucuture, that I use in my every godot project.

# Usage

For now just copy this structure to new project you've created
Later I'll add an automation script

# Structure

- `assets/` - game assets
- `scenes/` - scenes
- `resources/` - resources (builtin or custom)
- `scripts` - scripts
- `localizations/` - translation files (`.po(t)`, `.csv`)
- `themes/` - specifically theme resources (themes, styleboxes, etc)
- `shaders/` - shaders
- `.gdformatrc` - config file for `gdformat` formatter (see [godot-gdscript-toolkit](https://github.com/Scony/godot-gdscript-toolkit))
- `.gdlintrc` - linter rules config file for `gdlint` linter (see [godot-gdscript-toolkit](https://github.com/Scony/godot-gdscript-toolkit))
- `pre-commit` - pre-commit git hook to run formatter and linter (i usually just copy this file to `.git/hooks/`)
- `project.godot` - **WARNING: USE WITH CARE** - parts of project settings that i directly copy/paste across my project (use it only if you know how sections in `project.godot` work)
