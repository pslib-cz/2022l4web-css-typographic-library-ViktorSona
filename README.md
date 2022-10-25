# Typography.CSS library
**Author:** *Viktor Šona*

## Description
This CSS typography library should help you or give you inspiration in your own projects. Good luck with them.

## Demo site
Link to **[demo](https://pslib-cz.github.io/2022l4web-css-typographic-library-ViktorSona/)** site for preview.


## Navigator
1. [Implementation](#Implementation)
2. [Font](#Font)
3. [Headings](#Headings)
4. [Types of text](#Types-of-text)
5. [Cards](#Cards)
6. [Buttons](#Buttons)
7. [Images](#Images)
8. [Tables](#Tables)

## Implementation
1. Copy CSS **[docs/typography](https://github.com/pslib-cz/2022l4web-css-typographic-library-ViktorSona/blob/master/docs/typography.css)**
2. Paste to your CSS file
## Font
The font used throughout the web is called **[Kanit](https://fonts.google.com/specimen/Kanit?query=kani)**.
## Headings
You can use headings from `<h1>` to `<h5>`. Font sizes are: 
* 60px for `<h1>`
* 45px for `<h2>`
* 40px for `<h3>`
* 30px for `<h4>`
* 28px for `<h5>`
## Types of text
You can use these tags to change the font:
- `strong` for **Important text**<
- `i` for *Italic text*</i>
- `em` for <em>Emphasized text</em>
- `mark` for <mark>Marked text</mark>
- `small` for <small>Smaller text</small>
- `del` for <del>Deleted text</del>
- `ins` for <ins>Inserted text</ins>
- `sub` for <sub>Subscript text</sub>
- `sup` for <sup>Superscript tex</sup>
## Cards
Card is a flexible and extensible content container. It includes options for headers and footers, a wide variety of content, contextual background colors, and powerful display options.

Use this HTML style to properly apply the CSS preset:
```html
<section class="cards">
    <div class="card1">
        <div class="card__card1">
            <h5>text</h5>
        </div>
    </div>
    <div class="card2">
        <div class="card__card2">
            <h5>text</h5>
        </div>
    </div>
    <div class="card3">
        <div class="card__card3">
            <h5>text</h5>
        </div>
    </div>
</section>
```
## Buttons
CSS buttons refer to styled HTML buttons that developers customize to match their website designs. You can manipulate the colors, text sizes, padding, and even change styling properties when buttons enter different states.

I have preset three types of buttons with hover effects that interact:
- Use class `class="button--add"` for hoverable button button.
- Use class `class="button--cancel"` for disable look  button.
- Use class `class="button--continue"` for arrow-animated button.
## Images
CSS Images is a module of CSS that defines what types of images can be used (the image type, containing URLs, gradients and other types of images), how to resize them and how they and other replaced content, interact with the different layout models.

Use this HTML style to properly apply the CSS preset:
```html
<div class="container">
    <img src="img/image.jpg" alt="image" class="image">
    <div class="overlay">
     <div class="text">image</div>
    </div>
</div>
```
## Tables
A table in CSS is used to apply the various styling properties to the HTML Table elements to arrange the data in rows and columns, or possibly in a more complex structure in properly organized manner. Tables are widely used in communication, research, and data analysis. The table-layout property in CSS can be utilized to display the layout of the table. This property is basically used to sets the algorithm  that is used to layout table cells, rows, and columns.

The `<caption>` tag specifies the name of the table. We write everything that makes up the table into `<tbody>`. The `<tr>` tag defines a row in a table. In the `<tr>` tag, we write the `<th>` and `<td>` tags that make up the cells and write their contents into them. The `<th>` tag is for the cell heading. The `<td>` tag is for classic cells. The lines are alternately white and gray, the brackets are made in accordance with the design of the entire page. I hope you like it. :) 
```html
<table>
    <caption>Caption of the table</caption>
        <tbody>
            <tr>
                <th>Table Heading</th>
                <th>Table Heading</th>
                <th>Table Heading</th>
            </tr>
            <tr>
                <td>Item</td>
                <td>Item</td>
                <td>Item</td>
            </tr>
            <tr>
                <td>Item</td>
                <td>Item</td>
                <td>Item</td>
            </tr>
        </tbody>
```
