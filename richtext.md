---
title: Using the Rich Text Editor
layout: home
nav_order: 25
---

# Using the Rich Text Editor
The Umbraco Rich Text Editor is an editable field where you, as the editor, can be creative. You select how much you want to do yourself. You can work on text content, format the text, or leave it the way it is.

---

## How To Paste In External Content
While pasting content, the original text styles are preserved which can lead to different font faces, sizes, and colors displaying on the website when viewed. To prevent formatting issues, we recommended pasting the content first into a markdown editor such as notepad, then copy and paste it into your rich text editor.

Once you have your content pasted in the rich text editor, select all of your text and click the **Clear Formatting** button on the toolbar. This will remove inline styles from your selected content. Once you have done this, you can then add custom formats to your text as needed.

Remember to double-check that you don't have any empty paragraph tags after your content. This is common when pasting content into a rich text editor and can lead to unnecessary spacing at the end of your text.

---

## How To Apply Basic Formatting
{% include image_inline.html imageurl="images/basic-toolbar-formats.png" imagealt="Basic Toolbar Format Options" %}

1. Select the text you want to apply formats to.
1. Click the format button to apply the formatting.
<br />**NOTE:** When hovering over the toolbar options, a tooltip will appear telling you what the option is.

To undo a format, highlight the same text and click the same format to remove it. Alternatively, to remove all formatting, select the **Clear formatting** option.

---

## Working With Links
{% include alert_warning.html prefix="IMPORTANT:" text="When entering links, make sure to always use descriptive link text. Visitors using assistive technologies need descriptive link text to understand and navigate your content. For example, it's recommended to avoid using words like \"Click here\", \"Read more\", \"See all\" and instead use more descriptive language such as \"Subscribe to our blog\" or \"View the event schedule\"." %}

The **Insert/edit Link** button is used to add or update links to internal pages, external pages, media files, email links, and anchors. To insert different types of hyperlinks, follow the steps below.

### How To Link To A Page On Another Website
1. Highlight the text you want to hyperlink.
1. Click the **Insert Link** button.
1. In the **Link** field, enter the URL of the web page you wish to link to.
1. In the **Link title** field, enter the text that will be shown as a pointer to the link. This is an important information for everyone reading the website with different accessibility aids.
1. In the **Target** field, select the checkbox if you want the link to open in a new window or tab.
1. Click **Submit**.

### How To Link To A Page In Umbraco
1. Highlight the text you want to hyperlink.
1. Click the **Insert Link** button.
1. Select a page from the **Link to page** tree. The selection will populate the **Link** and **Link Title** fields.
1. In the **Link Title** field, enter the text that will be shown as a pointer to the link. By default, the name of the selected page will be populated.
1. In the **Target** field, select the checkbox if you want the link to open in a new window or tab.
1. Click **Submit**.

### How To Link To A Media File In Umbraco
1. Highlight the text you want to hyperlink.
1. Click the **Insert Link** button.
1. Select the **Select media** button.
1. Click **Select** on the media item you want to link to. The selection will populate the **Link** and **Link Title** fields.
1. In the **Target** field, select the checkbox if you want the link to open in a new window or tab.
1. Click **Submit**.

### How To Link To An Email Address
1. Highlight the text you want to hyperlink.
1. Click the **Insert Link** button.
1. In the **Link** field, enter the text **mailto**: followed by the email address you wish to link.
1. In the **Link Title** field, enter the text that will be shown as a pointer to the link.
1. In the **Target** field, select the checkbox if you want the link to open in a new window or tab.
1. Click **Submit**.

### How To Link To A Telephone Number
1. Highlight the text you want to hyperlink.
1. Click the **Insert Link** button.
1. In the **Link** field, enter the text **tel:** followed by the phone number you wish to link. Your telephone link should be formatted with hyphens, for example: tel:800-222-3333.
1. In the **Link Title** field, enter the text that will be shown as a pointer to the link.
1. In the **Target** field, select the checkbox if you want the link to open in a new window or tab.
1. Click **Submit**.

---

## Working With Images
{% include alert_note.html prefix="NOTE:" text="Make sure to <a href=\"media-manage.html#how-to-optimize-your-media\">optimize your images</a> before you upload them." %}

{% include alert_warning.html prefix="IMPORTANT:" text="Update the <strong>Alternative text</strong>, which is used by screen readers to describe the image to users with disabilities. By default, the image's \"name\" is set as the image description, which is typically something useless like \"IMG_9012.png.\" It's very important that the alt text accurately describes what's in the image and doesn't just repeat the file name. All non-decorative images need to have helpful image descriptions/alt text - this is a <a href=\"https://www.w3.org/TR/WCAG21/#text-alternatives\" target=\"_blank\">WCAG 2.1 accessibility</a> standard." %}

### How To Insert An Image From The Media Section
1. Place the cursor in the editor where you want to insert your image.
1. Click the **Media Picker** button in the toolbar.
1. Navigate through the Media library to locate where your image is stored.
1. Select the image and click **Choose**.
1. If applicable, enter **Alternative Text** for your image.<br/>
**IMPORTANT:** Utilize the <a href="https://www.w3.org/WAI/tutorials/images/decision-tree/" target="_blank">alt decision tree</a> to help determine when to use the alt attribute on images.
1. Click **Submit** to insert the image.

### How To Upload A New Image
You can upload images directly from your computer into the rich text editor. These images will be stored in the Umbraco Media library.

1. Place the cursor in the editor where you want to insert your image.
1. Click the **Media Picker** button in the toolbar.
2. Choose which folder you want the image to be uploaded in and click **Upload**.
**TIP:** You can also create a new folder by clicking the **+** icon next to the Media breadcrumb trail.
1. Select the file you want to upload from your computer.
1. With the newly-uploaded image selected, click **Choose**.
1. If applicable, enter **Alternative Text** for your image.<br/>
**IMPORTANT:** Utilize the <a href="https://www.w3.org/WAI/tutorials/images/decision-tree/" target="_blank">alt decision tree</a> to help determine when to use the alt attribute on images.
1. Click **Select** to insert the image.

---

## How To Insert A Table
1. Click on the **Table** icon in the editor toolbar and choose the amount of columns and rows through the grid selector.
1. Enter the table content into the outlined rows and columns.
2. Format the header row as a header row so it displays and functions correctly (details below).

### How To Format The Header Row
1. Highlight the first row of the table.
1. From the **Table** dropdown in the top toolbar choose **Row > Row Properties**.
1. Change the **Row Type** to **Header** and then click **OK**.
1. From the **Table** dropdown in the top toolbar choose **Cell > Cell Properties**.
1. Change the **Row Type** to **Header** and then click **OK**.

{% include alert_note.html prefix="NOTE:" text="Tables should only be used to render content that belongs naturally in a grid/spreadsheet or when data with the same set of properties are being compared. Tables should not be used for layout purposes. <a href=\"https://www.wearediagram.com/blog/content-best-practices-tips-to-achieve-a-more-successful-page\" target=\"_blank\">Learn more about table best practices</a>" %}

---

## How To Insert Inline Embed Code
1. Click on the **Insert Block** icon in the editor toolbar and choose **Inline Embed Block**.
1. Enter the applicable properties:
   1. **Backoffice Description:** Label that shows in the backoffice only to help clearly identify what the block is for. 
   2. **Intro Content:** Optional introductory content.
   3. **Embed Code:** External embed code snippet.
2. Click **Create**.

---

## How To Assign Custom Formats
1. Select/highlight the content you want to apply the formatting to.
1. Click the Formats dropdown and select a format.

| Option                        | Description                                                                                            |
| ----------------------------- | ------------------------------------------------------------------------------------------------------ |                                 
| Heading 2 Style               | Used to style regular non-heading text to look like an H2.                                             |
| Heading 3 Style               | Used to style regular non-heading text to look like an H3.                                             |
| Heading 4 Style               | Used to style regular non-heading text to look like an H4.                                             |
| Heading 5 Style               | Used to style regular non-heading text to look like an H5.                                             |
| Paragraph Large               | Increases the font size from standard to large. Typically used to introduce a page or section.         |
| Paragraph Small               | Decreases the font size from standard to small. Typically used for disclaimer or supplemental text.    |
| Alert Text                    | Highlights text in a warning alert style.                                                              |
| Info Text                     | Highlights text in an informational alert style.                                                       |
| Confirmation Text             | Highlights text in a confirmation alert style.                                                         |
| Error Text                    | Highlights text in an error alert style.                                                               |
| Primary Button                | Used for primary actions like submitting forms or signing up.                                          |
| Secondary Button              | Used for secondary actions or related links.                                                           |
| Float Right                   | Aligns an image to the right with content flowing on the left.                                         |
| Float Left                    | Aligns an image to the left with content flowing on the right.                                         |
| Clearfix                      | Clears left and right floats for the content that follows.                                             |

---

## How To Format Headings Appropriately
{% include alert_warning.html prefix="IMPORTANT:" text="Do not skip headings just to attain a better visual appeal. Using headings in the proper hierarchy not only helps with search engine optimization (SEO), but it also ensures that people using screen readers will be able to navigate through a page correctly." %}

The global CSS on a site determines how headings should appear, but headings aren’t just there to make text look pretty. They define a page’s structure and divide the text into different sections so users can easily scan a page and find the information they’re looking for. H1 headings should only be used for the page title, and H2 headings should be used to break up different high-level sections on the page. Then, within each high-level section, H3 and H4 headings are used to separate the content into even further sub-sections.

---

## How To View The HTML Source Code
To switch out of the WYSIWYG (what you see is what you get) editing mode and view the HTML code, click on the **View Source Code** icon in the toolbar. If any changes are made, click the **Submit** button before exiting out of the modal window. 
