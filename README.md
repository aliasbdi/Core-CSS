Core-CSS
========

A core set of CSS styles used to make common style definitions easier in HTML.

The Core CSS stylesheet includes an HTML5 reset (from Eric Meyer, http://meyerweb.com) to assure all Core CSS works properly. If you prefer to use your own reset, please be aware of inconsistencies.

Core CSS currently exists of a "positioning" styles used to position dom objects in the window. Each style has been specially named for ease of recall. For example, to force and change a dom to a block display, you only need to assign the class "block" to your element. "Inline" is used to force or change a dom to inline display.

(Please note that some names are commonly used by other frameworks like the class name "center" or "aligncenter" so an additional Core CSS file is included where all class names are prefixed with "cc-" so that "center" is now "cc-center" in order to prevent conflicts.)
