# Sublime Text Snippets for Hugo developement

## Installation

Package Control is coming in the mean time, you can just drop the files in there:

`/Users/thatUser/Library/Application Support/Sublime Text 3/Packages/User/`

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
Block | __block__ | `{{ block "main" . }} {{ end }}`
Block define | __define__ | `{{ define "block" }} {{ end }}`
Variable | __vars__ | `{{ $var := what }}`
Debug | __debug__ | `{{ printf "%#v"  }}`
Comment | __comm__ | `{{/* */}}`
