
# Fonts

* [Ubuntu Mono](http://font.ubuntu.com/)

# Themes

### Theme - Nil
### Theme - Soda
    {
        "theme": "Soda Dark.sublime-theme"
    }
### [Theme - Flatland](http://aspirecode.com/flatland-the-best-minimal-theme-for-sublime-text/)
    {
        // Optional theme, can use any
        "color_scheme": "Packages/Theme - Flatland/Flatland Dark.tmTheme",
        "theme": "Flatland Dark.sublime-theme"
    }
    
### [Tomorrow Color Schemes](https://github.com/chriskempson/tomorrow-theme)
    {
        "color_scheme": "Packages/Tomorrow Color Schemes/Tomorrow-Night.tmTheme"
    }

# Packages

### [Jade](https://github.com/davidrios/jade-tmbundle)

A comprehensive textmate / sublime text bundle for the Jade template language.

### [Less](https://github.com/danro/LESS-sublime)

LESS syntax highlighting for Sublime Text.

### [Coffee​Script](http://xavura.github.com/CoffeeScript-Sublime-Plugin)

Syntax highlighting and checking, commands, shortcuts, snippets, compilation and more.

### [SidebarEnhancements](https://github.com/titoBouzout/SideBarEnhancements/tree/st3)

Adds a bunch of options to the context menu in the sidebar.  Install from Package Control as "SideBarEnhancements".

### BracketHighlighter

Simple package to highlight selected open/close brackets/braces/parentheses.  Install from Package Control as "BracketHighlighter"

User settings: none

### SublimeLinter

Provides on-demand error checking of documents.  To get Coffeescript linting to work, use npm to install it, then restart Sublime Text.

npm install -g coffee-script

### Print to HTML

Adds File menu items to print the current document. It achieves this by generating a temp HTML file and opening it in a new browser, and optionally triggering the print dialog as well.  Has syntax highlighting and line numbers.

Install from Package Control as "Print to HTML"

User settings:  

    {
        "auto_print_in_browser" : false,
        "auto_close_in_browser" : false,
        "font_face": "Ubuntu Mono",
        "font_size": "100%"
    }

### Web Inspector

Can be used to debug Chrome via Sublime Text 2.  Not tested.  Installed via Package Control as "Web Inspector"