# NOTES ITCSS

This is a general documents with my insights about ITCSS

## Triangle

| Triangle elements | +Info         | Description      |
| ----------------- | ------------- | ---------------- |
| SETTINGS          | [^settings]   | used with pre... |
| TOOLS             | [^tools]      | globally used... |
| GENERIC           | [^generic]    | reset and/or...  |
| ELEMENTS          | [^elements]   | styling for...   |
| OBJECTS           | [^objects]    | class-based s... |
| COMPONENTS        | [^components] | specific UI...   |
| UTILITIES         | [^utilities]  | utilities and... |

[^settings]:  used with preprocessors and contain font, colors definitions, etc.
[^tools]:  globally used mixins and functions. It’s important not to output any CSS in the first 2 layers.
[^generic]:  reset and/or normalize styles, box-sizing definition, etc. This is the first layer which generates actual CSS.
[^elements]:  styling for bare HTML elements (like H1, A, etc.). These come with default styling from the browser so we can redefine them here.
[^objects]:  class-based selectors which define undecorated design patterns, for example media object known from OOCSS
[^components]:  specific UI components. This is where the majority of our work takes place and our UI components are often composed of Objects and Components
[^utilities]:  utilities and helper classes with ability to override anything which goes before in the triangle, eg. hide helper class

## URLs
- [XFIVE ITCSS: Scalable and Maintanable CSS Architecture](https://www.xfive.co/blog/itcss-scalable-maintainable-css-architecture/) 
- [An introduction to Object Oriented CSS (OOCSS)](https://www.smashingmagazine.com/2011/12/an-introduction-to-object-oriented-css-oocss/)


## TODO
- [ ] create a repo with and schaffold structure

