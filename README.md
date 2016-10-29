# Atom-file-icons-for-browser
Modification of @DanBrooker [file-icons](https://github.com/DanBrooker/file-icons) Atom package to work in browser.

Includes stylings/icons for .file-text-o and .folder-open for file and folder icons respectively as well as default "?" icon for icons either improperly called or not in file-icons.less.

Also includes alternate font formats for some fonts.

## Getting started

First steps:
  1. Download or clone this repo
  2. Use [less.js](http://lesscss.org/) either by `npm install -g less` or by including less from their CDN \n
  ```html
  <script src="//cdnjs.cloudflare.com/ajax/libs/less.js/2.7.1/less.min.js"></script>
  ```
  3. Import file-icons.less in your browser from whichever directory you have configured for serving files like so: \n
  ```html
  <link rel="stylesheet/less" href="/stylesheets/file-icons.less">
  ```
  This should import the other relevant .less files as well as define the font faces available.

## How to Use

Just define the attribute data-name="" inside of any HTML tag with the file extension, and the relevant icon should be placed ```less :before ``` the tag.
Example:
```html
<span data-name=".atom"></span>
```

This works for all icons in the examples directory of Atom file-icons which can be found here: [file-icons/example](https://github.com/DanBrooker/file-icons/tree/master/examples)


## TO DO:

1. Include complete set of icons from Octicons, and other fonts.
2. Get color/black & white toggling working
3. MOAR ICONS!!!!!!!!
