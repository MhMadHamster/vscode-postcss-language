# postcss-language

VSCode language support for PostCSS and SugarSS

package is based on [Syntax Highlighting for PostCSS](https://github.com/hudochenkov/Syntax-highlighting-for-PostCSS)

## Features

Syntax highlighting for:  
``.pcss``  
``.postcss``  
``.sss``

if you want this plugin to work for ``*.css`` file you need manually change "Language mode" in VSCode to ``PostCSS`` or add  
```
"files.associations": {
  "*.css": "postcss"
}
```  
to your ``settings.json`` (File -> Preferences -> Settings) if you want to treat all css files as postcss by default

# Change Log
## [2.0.0]
### Added
- Support for color decorators and CSS IntelliSense.

### Changed
- Extension now using a language-server(based on vscode-css-extension and vscode-css-languageservice) and a language-client for an additional functionality, such as color decorators.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## Known Issues

semicolon automatically added when expanding abbreviation in *.sss files