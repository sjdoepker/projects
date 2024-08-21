did you know: CSS variables can be updated with Javascript? (unlike SASS, where they're defined at compile time and are immutable)

input type "color" gives you a color picker!

CSS variables: declared on an element (or on "root", highest possible level, where you set the default)
defined by `--varName`

querySelectorAll returns a NodeList (not an array); *cannot* use array methods (e.g. filter, find, map)

data-sizing attribute is custom and lets us pass raw numbers (10, 50, etc.) from the input to HTML without having to worry about them
not being in px or em or whatever 

dataset takes all data attributes assigned to the object and packages them together

note that you can also scope CSS variables to just be on a specific div (e.g. specifiy h2's base explicitly and it will win); lower/smaller scope overrides larger/higher scope