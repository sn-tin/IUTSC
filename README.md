# IUTSC
## Table of contents
  - [Important parts in the code that should not be left out](#important-parts-in-the-code-that-should-not-be-left-out)
  - [Lyrics Show All](#lyrics-show-all)
  - [Lyrics Single Page](#lyrics-single-page)
## Important parts in the code that should not be left out
### Add a space on the HTML format, height can be adjusted by changing the value, for example: style="height:{value}px”
```<div style="height:30px" class="wp-block-spacer"></div>```
### Usage of the Read More plugin. Paragraph that should be hidden must be enclosed with [read more] [/read] tags 
```[read more] paragraph that you want to hide [/read]```
### For titles such as ALBUM INTRODUCTION and SONG INTRODUCTIONS, it should be enclosed with <h3></h3> tag 
```<h3>SONG INTRODUCTIONS</h3>```
### Italicizing a paragraph should be enclosed in <em></em> tag
```<em>Lyrics by IU</em>```
### Link format for the “See Lyrics”
It must be enclosed with ``` <strong></strong>``` tag to make it bold and ```<a href="example-link.com">Text</a>``` tag to create a clickable link. **DO NOT** include the domain of the site (https://staging-ed43-iutsxxx.xxx.com/ or https://iutxx.com/): <br />
**Correct format:**
```<strong><a href="/lyrics-iu-아이유-라일락-lilac/" class="lyrics-title-label" style="text-decoration: underline;">See lyrics</a></strong>```
### NOTES FOR SINGLE LYRICS PAGE ONLY:
### Each block of lyrics must be enclosed with ```<p></p>``` tag
Don't forget the ```<br>``` tag to add a line break. Otherwise, it will appear as a whole paragraph. <br />
**Correct Format:**
``<p>My eyes sting from the flying pollen (ouch)<br>
Though tears swell in my eyes, I’ll endure it<br>
I’ll keep it in a secret orgel box in the corner of my heart<br></p>``

## Lyrics Show All
### Example Code & Reference Page
- PAGE - [Lilac Album](https://staging-ed43-iutsccom.wpcomstaging.com/lilac/)
- CODE - [Lilac Album Code Format](https://github.com/sn-tin/IUTSC/blob/main/iutsc-format](https://github.com/sn-tin/IUTSC/blob/main/iutsc-format)https://github.com/sn-tin/IUTSC/blob/main/iutsc-format)

## Lyrics Single Page
**Example Code & Reference Page**
- PAGE - [Lilac (Title Song) Single Page Lyrics](https://staging-ed43-iutsccom.wpcomstaging.com/lyrics-iu-%ec%95%84%ec%9d%b4%ec%9c%a0-%eb%9d%bc%ec%9d%bc%eb%9d%bd-lilac/)
- CODE - https://github.com/sn-tin/IUTSC/blob/main/iutsc-single-page-format


