# Sublime Text Snippets for [Hugo](https://gohugo.io)

## Installation

### With Package Control

[Package Control: Install Package](https://packagecontrol.io/docs/usage) and look for `Hugo Snippets`

### With Git

#### OSX

    $ cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User
    $ git clone git@github.com:regisphilibert/Sublime-Hugo-Snippets.git

#### Linux (Ubuntu like distros)

    $ cd ~/.config/sublime-text-3/Packages/User
    $ git clone git@github.com:regisphilibert/Sublime-Hugo-Snippets.git
    
## Available Snippets

Snippet | Tab Trigger | Output
--- | --- | ---
Curlies | __x__ | `{{ }}`
Dot | __dot__ | `{{ . }}`
If | __if__ | `{{ if }} {{ end }}`
If/Else | __ife__ | `{{ if }} {{ else }} {{ end }}`
If/Else if | __ifei__ | `{{ if }} {{ else if }} {{ end }}`
With | __with__ | `{{ with }} {{ end }}`
With/Else | __withe__ | `{{ with }} {{ else }} {{ end }}`
Range | __range__ | `{{ range  }} {{ end }}`
Partial | __partial__ | `{{ partial "" . }}`
Shortcode | __short__ | `{{< shortcode arg >}}`
Block | __block__ | `{{ block "main" . }} {{ end }}`
Block define | __define__ | `{{ define "block" }} {{ end }}`
Variable | __vars__ | `{{ $var := what }}`
Debug | __debug__ | `{{ printf "%#v"  }}`
Comment | __comm__ | `{{/* */}}`
