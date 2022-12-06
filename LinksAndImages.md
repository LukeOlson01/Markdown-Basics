## Links and Images
Links are written using brackets `[]` and parenthesis `()`. The link is placed in the parenthesis and the text that is displayed for the link in the output is placed in the brackets.  
A link could be written like:
```
[click here to go to google](https://www.google.com/)
```
The output will be:

[click here to go to google](https://www.google.com/)

Instead of having the link directly provided with the link text, you can have a reference to the link provided with the link text. The link that the reference is associated with can be defined at the bottom of the Markdown page and won't be displayed. This is useful if you want to have multiple links that all go to the same place.  
A reference link can be written like:
```
[this is a link to google][reference to google]
[this is another link to google][reference to google]

[reference to google]: https://www.google.com/
```
The output will be:

[this is a link to google][reference to google]  
[this is another link to google][reference to google]

[reference to google]: https://www.google.com/

Images work in a similar way to links. Images use brackets `[]` and parenthesis `()`. The image link is placed in the parenthesis and the alt text is placed in the brackets. Unlike links, when creating images, an exclamation point `!` must be placed in front of the brackets.  
An image can be created like:
```
![This is the alt text for the image](This is the image link)
```
[< Lists](Lists.md) | [Additional Syntax >](AdditionalSyntax.md)
