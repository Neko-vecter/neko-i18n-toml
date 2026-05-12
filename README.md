# Meow i18n.toml

## About this extension

Meow i18n.toml is a specialized syntax highlighting extension for TOML files used in internationalization (i18n) workflows.

Standard TOML highlighters often treat all strings the same. This extension provides enhanced visual differentiation for origin (source text) and translate (target text) fields, helping developers and translators navigate large translation blocks with ease and precision.

## Key Features

- Semantic Highlighting: Optimized specifically for key, origin, and translate patterns.
- Structure Visualization: Clearer separation of `[[block]]` elements to keep your translation files organized.
- Semantic Key Highlighting: Identifies key, origin, and translate as specific functional tokens rather than generic strings for a more intuitive editing experience.

## Example of i18n.toml

```toml
[metadata]

[[block]] 
key = "3a9d397ac5618c86"
origin = '''
This is the original source text that needs translation.
It can span multiple lines comfortably.
'''
translate = '''
This is the translated text in the target language.
The extension makes these blocks easy to distinguish.
'''
```
