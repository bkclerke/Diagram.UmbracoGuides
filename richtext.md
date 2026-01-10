---
title: Using the Rich Text Editor
layout: home
nav_order: 25
---

# Using the Rich Text Editor

The Umbraco Rich Text Editor is an editable field where you, as the editor, can be creative. You select how much you want to do yourself. You can work on text content, format the text, or leave it the way it is.

## How To Paste In External Content
While pasting content, the original text styles are preserved which can lead to different font faces, sizes, and colors displaying on the website when viewed. To prevent formatting issues, we recommended pasting the content first into a markdown editor such as notepad, then copy and paste it into your rich text editor.

Once you have your content pasted in the rich text editor, select all of your text and click the **Clear formatting** button on the toolbar. This will remove inline styles from your selected content. Once you have done this, you can then add custom formats to your text as needed.

Remember to double-check that you don't have any empty paragraph tags after your content. This is common when pasting content into a rich text editor and can lead to unnecessary spacing at the end of your text.

## How To Apply Basic Formatting
{% include image_inline.html imageurl="images/basic-toolbar-formats.png" imagealt="Basic Toolbar Format Options" caption="Basic Toolbar Format Options" %}

1. Select the text you want to apply formats to.
1. Click the format button to apply the formatting.
<br />**NOTE:** When hovering over the toolbar options, a tooltip will appear telling you what the option is.

To undo a format, highlight the same text and click the same format to remove it. Alternatively, to remove all formatting, select the **Clear formatting** option.

## Working With Links
{% include alert_warning.html prefix="IMPORTANT:" text="When entering links, make sure to always use descriptive link text. Visitors using assistive technologies need descriptive link text to understand and navigate your content. For example, it's recommended to avoid using words like \"Click here\", \"Read more\", \"See all\" and instead use more descriptive language such as \"Subscribe to our blog\" or \"View the event schedule\"." %}

The **Insert/edit Link** button is used to add or update links to internal pages, external pages, media files, email links, and anchors. To insert different types of hyperlinks, follow these steps:

### How To Link To A Page On Another Website
1. Select the text for the hyperlink.
1. Click the **Insert Link** button. The **Select Link** tree 1. opens on the right-side of the editor.
1. In the **Link** field, enter the URL of the web page you wish to link to.
1. In the **Link title** field, enter the text that will be shown as a pointer to the link. This is an important information for everyone reading the website with different accessibility aids.
1. In the **Target** field, select the checkbox if you want the link to open in a new window or tab.
1. Click **Submit**.

### How To Link To A Page In Umbraco
1. Select the text for the hyperlink.
1. Click the **Insert Link** button. The **Select Link** tree opens on the right-side of the editor.
1. Select a page from the **Link to page** tree. The selection will populate the **Link** and **Link Title** fields.
1. In the **Link Title** field, enter the text that will be shown as a pointer to the link. By default, the name of the selected page will be populated.
1. In the **Target** field, select the checkbox if you want the link to open in a new window or tab.
1. Click **Submit**.

### How To Link To A Media File In Umbraco
1. Select the text for the hyperlink.
1. Click the **Insert Link** button. The **Select Link** tree opens on the right-side of the editor.
1. Select the **Select media** button. The **Select media** tree opens where you can select the media item.
1. Click **Select**. The selection will populate the **Link** and **Link Title** fields.
1. In the **Target** field, select the checkbox if you want the link to open in a new window or tab.
1. Click **Submit**.

### How To Link To An Email Address
1. Select the text for the hyperlink.
1. Click the **Insert Link** button. The **Select Link** tree opens on the right-side of the editor.
1. In the **Link** field, enter the text mailto: followed by the email address you wish to link.
1. In the **Link Title** field, enter the text that will be shown as a pointer to the link.
1. In the **Target** field, select the checkbox if you want the link to open in a new window or tab.
1. Click **Submit**.

### How To Link To A Telephone Number
1. Select the text for the hyperlink.
1. Click the **Insert Link** button. The **Select Link** tree opens on the right-side of the editor.
1. In the **Link** field, enter the text tel: followed by the phone number you wish to link. Your telephone link should be formatted with hyphens, for example, your link will look like tel:800-222-3333.
1. In the **Link Title** field, enter the text that will be shown as a pointer to the link.
1. In the **Target** field, select the checkbox if you want the link to open in a new window or tab.
1. Click **Submit**.

## Working With Images

[comment]: TODO: hyperlink the optimize your images

{% include alert_note.html prefix="NOTE:" text="Make sure to <a href=\"#\">optimize your images</a> before you upload them." %}

{% include alert_warning.html prefix="IMPORTANT:" text="Update the <strong>Alternative text</strong>, which is used by screen readers to describe the image to users with disabilities. By default, the image's \"name\" is set as the image description, which is typically something useless like \"IMG_9012.png.\" It's very important that the alt text accurately describes what's in the image and doesn't just repeat the file name. All non-decorative images need to have helpful image descriptions/alt text - this is a <a href=\"https://www.w3.org/TR/WCAG21/#text-alternatives\" taget=\"_blank\">WCAG 2.1 accessibility</a> standard." %}

### How To Insert An Image From The Media Section
1. Place the cursor in the editor where you want to insert your image.
1. Click the **Media Picker** button on the toolbar. The **Select Media** tree opens on the right-side of the editor.
1. Select the folder in which your image is stored.
1. Click the thumbnail of the image. The **Edit selected media** tree opens.
1. Enter an **Alternative Text** for your image.
1. Click **Select** to add the image.

### How To Insert An Image From Your Computer
You can upload images directly from your local directory in the rich text editor. These images will be stored in the Umbraco media library. Ensure that the image is placed in the correct location within the library.

You can also create folders in the media library by clicking the + icon next to Media/.

To insert an image from your computer:
1. Place the cursor in the editor where you want to insert your image.
1. Click the **Media Picker** button. The **Select Media** tree opens on the right-side of the editor.
1. Click the **Upload** button in the top-right corner of the tree.
1. Browse to the directory, select the image, and click **Open**.
1. Enter an **Alternative Text** for your image.
1. Click **Select** to add the image.

## How To Insert A Table
1. Click on the **Table** icon in the editor toolbar and choose the amount of columns and rows through the grid selector.
1. Enter the table content into the outlined rows and columns.

### How To Format The Header Row
1. Highlight the first row of the table.
1. From the **Table** dropdown in the top toolbar choose **Row > Row Properties**.
1. Change the **Row Type** to **Header** and then click **OK**.
1. From the **Table** dropdown in the top toolbar choose **Cell > Cell Properties**.
1. Change the **Row Type** to **Header** and then click **OK**.

{% include alert_note.html prefix="NOTE:" text="Tables should only be used to render content that belongs naturally in a grid/spreadsheet or when data with the same set of properties are being compared. Tables should not be used for layout purposes. <a href=\"https://www.wearediagram.com/blog/content-best-practices-tips-to-achieve-a-more-successful-page\" target=\"_blank\">Learn More</a>" %}

## How To Insert Inline Embed Code
1. Click on the **Insert Block** icon in the editor toolbar and choose **Inline Embed Block**.
1. Enter the applicable properties:
   1. **Backoffice Description:** Label that shows in the backoffice only to help clearly identify what the block is for. 
   2. **Intro Content:** Optional introductory content.
   3. **Embed Code:** External embed code snippet.
2. Click **Create**.

## How To Assign Custom Formats
1. Select the text you want to apply the formatting to.
1. Click the Formats dropdown and select a format.

[comment]: TODO: Update table examples and custom format options

| Option                        | Description                                                                                            | Example / Notes                  |
| ----------------------------- | ------------------------------------------------------------------------------------------------------ | -------------------------------- |
| Heading 2                     | Sets the selected text to an H2.                                                                       |                                  |
| Heading 3                     | Sets the selected text to an H3.                                                                       |                                  |
| Heading 4                     | Sets the selected text to an H4.                                                                       |                                  |
| Heading 5                     | Sets the selected text to an H5.                                                                       |                                  |
| Heading 2 Style               | Used to style regular non-heading text to look like an H2.                                             | Example                          |
| Heading 3 Style               | Used to style regular non-heading text to look like an H3.                                             | Example                          |
| Heading 4 Style               | Used to style regular non-heading text to look like an H4.                                             | Example                          |
| Heading 5 Style               | Used to style regular non-heading text to look like an H5.                                             | Example                          |
| Footer Header                 | Used to style headings in the footer area. **Note:** Only applies in the site settings rich text area. |                                  |
| Paragraph Large               | Increases the font size from standard to large. Typically used to introduce a page or section.         | Example                          |
| Paragraph Small               | Decreases the font size from standard to small. Typically used for disclaimer or supplemental text.    | Example                          |
| Blockquote                    | Used to format text as a pull quote.                                                                   | “This is an example blockquote.” |
| Ruled List                    | Styles a list by removing bullets/numbers and adding ruled lines between items.                        | Ruled list example               |
| Agenda List                   | Styles a list (intended for agendas) by adding ruled lines between items.                              | Agenda list example              |
| Alert Text                    | Highlights text in a warning alert style.                                                              | Example alert text               |
| Info Text                     | Highlights text in an informational alert style.                                                       | Example info text                |
| Confirmation Text             | Highlights text in a confirmation alert style.                                                         | Example confirmation text        |
| Error Text                    | Highlights text in an error alert style.                                                               | Example error text               |
| Vertical Align Top            | Sets vertical alignment of table content to the top.                                                   |                                  |
| Vertical Align Middle         | Sets vertical alignment of table content to the middle.                                                |                                  |
| Vertical Align Bottom         | Sets vertical alignment of table content to the bottom.                                                |                                  |
| Primary Button                | Used for primary actions like submitting forms or signing up.                                          | Primary button link              |
| Primary Button (Full Width)   | Displays the primary button at full width.                                                             | Full-width primary button        |
| Secondary Button              | Used for secondary actions or related links.                                                           | Secondary button link            |
| Secondary Button (Full Width) | Displays the secondary button at full width.                                                           | Full-width secondary button      |
| Button Row                    | Displays multiple buttons in a single horizontal row when applied to a list.                           | View example                     |
| Float Right                   | Aligns an image to the right with content flowing on the left.                                         | View example                     |
| Float Left                    | Aligns an image to the left with content flowing on the right.                                         | View example                     |
| Clearfix                      | Clears left and right floats for the content that follows.                                             |                                  |

### Format Headings Appropriately

{% include alert_warning.html prefix="IMPORTANT:" text="Do not skip headings just to attain a better visual appeal. Using headings in the proper hierarchy not only helps with search engine optimization (SEO), but it also ensures that people using screen readers will be able to navigate through a page correctly." %}

The global CSS on a site determines how headings should appear, but headings aren’t just there to make text look pretty. They define a page’s structure and divide the text into different sections so users can easily scan a page and find the information they’re looking for. H1 headings should only be used for the page title, and H2 headings should be used to break up different high-level sections on the page. Then, within each high-level section, H3 and H4 headings are used to separate the content into even further sub-sections.

## How To View The HTML Source Code

To switch out of the WYSIWYG (what you see is what you get) editing mode and view the HTML code, click on the **View Source Code** icon in the toolbar. If any changes are made, click the **Submit** button before exiting out of the modal window. 