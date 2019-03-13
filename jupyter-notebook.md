## Jupyter Notebook Mardowns

**Headings**: Use #s followed by a blank space for notebook titles and section headings:
- ` # title `
- ` ## major headings ` 
- ` ### subheadings ` 
- ` #### 4th level subheadings ` 

**Emphasis**: 
- Bold: `__string__` or `**string**` 
- Italic: `_string_` or `*string*`

**Mathematical symbols**: Use this code: `$ mathematical symbols $`

Monospace font: Surround text with a back single quotation mark. (`) Use monospace for file path and file names and for text users enter or message text users see.

Line breaks: Sometimes markdown doesn’t make line breaks when you want them. Use this code for a manual line break: <br>.

Colors: Use this code: <font color=blue|red|green|pink|yellow>Text</font> Not all markdown code works within a font tag, so review your colored text carefully!

Indenting: Use a greater than sign (>) and then a space, then type the text. Everything is indented until the next carriage return.

Bullets: Use the dash sign (- ) with two spaces after it or a space, a dash, and a space ( - ), to create a circular bullet. To create a sub bullet, use a tab followed a dash and two spaces. You can also use an asterisk instead of a dash, and it works the same.

Numbered lists: Start with 1. followed by a space, then it starts numbering for you. Start each line with some number and a period, then a space. Tab to indent to get subnumbering.

Graphics: You can attach image files directly to a notebook only in Markdown cells. Drag and drop your images to the Mardown cell to attach it to the notebook. To add images to other cell types, you can use only graphics that are hosted on the web. You can’t add captions for graphics at this time. Use this code: <img src="url.gif" alt="Alt text that describes the graphic" title="Title text" />

Geometric shapes: Use this code with a decimal or hex reference number from here: UTF-8 Geometric shapes
 &#reference_number

Horizontal lines: Use three asterisks: ***

Internal links: To link to a section, use this code: [section title](#section-title) For the text in the parentheses, replace spaces and special characters with a hyphen. Make sure to test all the links!

Alternatively, you can add an ID for a section right above the section title. Use this code: <a id="section_ID"></a> Make sure that the section_ID is unique within the notebook.

Use this code for the link and make sure to test all the links! [section title](#section_ID)

External links: Use this code and test all links! __[link text](http://url)__
