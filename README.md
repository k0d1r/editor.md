
---

### Features

- Offers support for both Standard Markdown/CommonMark and GitHub Flavored Markdown (GFM);
- Encompasses a wide range of functionalities: Real-time Preview, Image upload with cross-domain support, Insertion of preformatted text/code blocks/tables, Code folding, Search and replace capabilities, Read-only mode, Multiple themes, Support for multiple languages and localization (L18n), HTML entity handling, and Syntax highlighting for code;
- Markdown Extensions: Adds support for Table of Contents (ToC), Emojis, Task lists, and @mentions;
- Ensures compatibility across all major browsers (IE8+), along with support for Zepto.js and optimal performance on iPad;
- Facilitates safe parsing and filtering of HTML tags;
- Expands Markdown syntax to include support for TeX mathematical expressions (via KaTeX), Flowcharts, and Sequence Diagrams;
- Integrates with AMD/CMD module loaders such as Require.js & Sea.js, enabling customization and definition of editor plugins;

# Editor.md

![Editor.md Logo](https://github.com/kadoiOS/editor.md/raw/master/examples/images/logos/editormd-logo-180x180.png)

![GitHub Stars](https://img.shields.io/github/stars/kadoiOS/editor.md.svg) 

![GitHub Forks](https://img.shields.io/github/forks/kadoiOS/editor.md.svg) 

![GitHub Tags](https://img.shields.io/github/tag/kadoiOS/editor.md.svg) 

![GitHub Release](https://img.shields.io/github/release/kadoiOS/editor.md.svg) 

![GitHub Issues](https://img.shields.io/github/issues/kadoiOS/editor.md.svg) 

![Bower Version](https://img.shields.io/bower/v/editor.md.svg)

**Table of Contents**

[TOCM]

[TOC]

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
# Link to Heading 1 [Heading link](https://github.com/kadoiOS/editor.md "Heading link")
## Link to Heading 2 [Heading link](https://github.com/kadoiOS/editor.md "Heading link")
### Link to Heading 3 [Heading link](https://github.com/kadoiOS/editor.md "Heading link")
#### Link to Heading 4 [Heading link](https://github.com/kadoiOS/editor.md "Heading link")
##### Link to Heading 5 [Heading link](https://github.com/kadoiOS/editor.md "Heading link")
###### Link to Heading 6 [Heading link](https://github.com/kadoiOS/editor.md "Heading link")

## Headers (Alternative Formatting)

H1 Header (Alternative Style)
=============

H2 Header (Alternative Style)
-------------

### Text Styling
                
----

~~Strikethrough~~ <s>Strikethrough (HTML tags enabled)</s>
*Italic* _Italic_
**Bold** __Bold__
***Bold Italic*** ___Bold Italic___

Superscript: X<sub>2</sub>, Subscript: O<sup>2</sup>

**Abbreviations (HTML abbr tag)**

The <abbr title="Hyper Text Markup Language">HTML</abbr> standard is overseen by the <abbr title="World Wide Web Consortium">W3C</abbr>.

### Blockquotes

> Example Blockquote

Text Formatting
                    
> "A notable quote", [Source Link](http://example.com)。

### Hyperlinks

[Link Example](http://example.com)

[Link with Title](http://example.com "Link Title")

`<Link>` : <https://github.com>

[Reference Link][ref] 

[ref]: http://example.com/

GFM Auto-linking @username

### Code Snippets (Multiple Languages) & Syntax Highlighting

#### Inline Code

`$ npm install package-name`

#### Code Blocks (Indented Style)

Indented 4 spaces, resembling `<pre>` tags.

    <?php
        echo "Sample code!";
    ?>
    
Indented Code Blocks (For Tables):

    | Header 1     | Header 2     |
    | ------------ | ------------ |
    | Row 1, Cell 1| Row 1, Cell 2|
    | Row 2, Cell 1| Row 2, Cell 2|

#### JavaScript Example

```javascript
function sampleFunction(){
	console.log("Sample output!");
}
 
(function(){
    var module = function(){
        return module.fn.init();
    };

    module.prototype = module.fn = {
        init : function(){
            console.log('module.init()');

			return this;
        },

		add : function(str){
			alert("Added", str);

			return this;
		},

		remove : function(str){
		

	alert("Removed", str);

			return this;
		}
    };
    
    module.fn.init.prototype = module.fn;
    
    window.module = module;
})();

var myModule = module();
myModule.add("Example").remove("Example");
```

#### HTML Sample Code

```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8" />
        <title>Sample Title</title>
    </head>
    <body>
        <h1>Sample Heading</h1>
    </body>
</html>
```
