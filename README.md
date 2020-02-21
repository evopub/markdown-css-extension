# MARKDOWN CSS EXTENSION 

**Display images where you want and at the size you want, controle alignment of text (center, right-align),..., all that directly in your markdown file** 

## Version 

- 2.0: 21 february 2020: add responsive break in image code  
- 1.1: 4 july 2019 : Typo Correction
- 1.0: 16 november 2018: First public version 

## Installation 

1. Download or clone the file `apg_markdown_extension.min.css` (3 KB) and upload it to your server  
2. Add the line `<link rel="stylesheet" type="text/css" href="apg_markdown_extension.min.css">` at the end of the HEAD section of your HTML file (or paste its content at the end of your CSS file)  
3. Use the markup in your Markdown file as indicated below 

## How to use 

### Markdown Image Code: 

Allows to change the size, the alignment, the margin, and the style of the image: just add the following codes between the [] in Markdown Image code. 

New in version 2.0: you can define the minimum treshold under which the size is not applied (`fullxs`, `fullsm`, `fullmd`, `fulllg`)

See Example at: <http://gouillou.com/scripts/markdown-css-extension.html> 

#### The codes 

- **Size :**  
	- **Width :** sixth, third, half, twothird, full, 100, 100sq, 150, 150sq, 200, 400, 450, 600  
		- **Full widh under treshold (new in v 2.0):** fullxs, fullsm, fullmd, fulllg  
	- **height :** h50, h100, h200, hfull  
- **Align :** center, left, right  
- **Margin :** m0, m1  
- **Style :** 3d, circle, rounded 

#### How to modify 

The "codes" are just CSS class names: you can do what you want easily. 

## Markdown Blockquote Code 

Allows to change the appearance of text by using the blockquode mark (>) 

See Examples of use of each code at: <http://gouillou.com/scripts/markdown-css-extension.html> 

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

