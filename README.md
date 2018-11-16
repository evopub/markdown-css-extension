# markdown-css-extension

**Display images where you want and at the size you want, controle alignment of text (center, right-align), ..., all that directly in your markdown file**

## Installation

1. Download or clone the file `apg_markdown_extension.css` and upload it to your server
2. Add the line `<link rel="stylesheet" type="text/css" href="apg_markdown_extension.css">` at the end of the HEAD section of your HTML file (or paste its content at the end of your CSS file)
3. Use the markup in your Markdown file as indicated below



## How to use

### Markdown Image Code:

Allows to change the size, the alignment, the margin, and the style of the image: just add the following codes between the [] in Markdown Image code. 

#### Example 

See Example at: <http://gouillou.com/markdown-css-extension.html> 

#### The codes
- **Size :** 
	 - **Width :** sixth, third, half, twothird, full, 100, 100sq, 150, 150sq, 200, 400, 450, 600
	- **height :** h50, h100, h200, hfull
- **Align :** center, left, right
- **Margin :** m0, m1
- **Style :** 3d, circle, rounded

#### How to modify

The "codes" are just CSS class names: you can do what you want easily.


## Markdown Blockquote Code

Allows to change the appearance of text by using the blockquode mark (>)

#### Examples 

See Examples of use of each code at: <http://gouillou.com/markdown-css-extension.html> 


#### The codes

	> (1) Blockquote normal
	>> (2) Grey background
	>>> (3) Text-Align: Center
	>>>> (4) Text-Align: Right 
	>>>>> (5) Display as H2 without numerotation neither inclusion in TOC
	>>>>>> (6) Exergue
	>>>>>>> (7) Exergue with blue line

#### How to modify

You'll probably want to change the fonts indicated in the script. Beware: because of the cascade of blockquotes, the changes are more difficult (check the consequences!)

