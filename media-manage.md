---
title: Media Management
layout: home
nav_order: 12
---

# Media Management
The Media section stores all the media that is uploaded and used on your website. You can view all your stored media in hierarchical order within the media tree.

---
## Organize Your Media
Folders help organize the Media section and keep similar media items in a logical structure. We recommend using folders to organize your media items by site and media type.

You can further organizing media by its use (block types), size ratios, pages, or whatever else makes it easier for you to find your media.

### How To Create Media Folders
1.  To create a media folder, go to the Media section and click **•••** next to the parent node you wish to create a folder underneath. Alternatively, you can right-click the node and click **Create**. [View](https://www.natptax.com/media/xvaj2xcb/media-create-menu.png)
2.  From the list of available media types, select **Folder**.
3.  Enter a name for the folder.
4.  Click **Save**.

### How To Rename Folders
1.  Navigate to the Media section and select the folder in the media tree.
2.  Edit the folder **Name**.
3.  Click **Save**.

---
## How To Delete Media
Deleting content and media in Umbraco works the same. Check out how to use the [Recycle Bin](./content-management.html#recycle-bin).

---
## Optimizing Your Media
It's important to make sure that you optimize your media before you upload it to the Media section.

Optimizing your media consists of:
1.  Cropping your image to correct dimensions/aspect ratios.
2.  Compressing your file sizes. **NOTE:** Multiple [free tools](https://imageresizer.com/image-compressor) exist to compress image file sizes.
3.  Renaming your media file names. Utilize hyphens instead of spaces or other symbols in the file name. This is important for SEO and accessibility.

---
## How To Upload Media

### Using the Umbraco Media Section
**IMPORTANT:** Before uploading your media, make sure you optimize your media first and select the correct upload location to organize your media.

In the Media section, you can upload media in three ways:
1.  Drag and drop your files in the **Upload** field in the Media section.**NOTE:** Make sure you have your folder selected first to keep your media organized. [View](https://www.natptax.com/media/3txfjvv0/media-upload-section.png)
2.  Click **•••** next to **Media** and choose the media type, enter a name for your media item and select the **Click to upload** field to choose a file type or drag the file into the upload field to upload the item.
3.  Click the **Create** dropdown, and choose the media item. Enter a name for your media item and select the **Click to upload** field or drag the file into the upload field to upload the item. [View](https://www.natptax.com/media/xuuf5qd0/media-create-action-menu.png)

---
## Optimizing Your SVG Files
When uploading SVG files to the media section it is important to check a few options in the SVG file itself to confirm that the SVG graphic will display correctly on the website.

1.  If your SVG file is used for decoration, ensure that the tag has the role="presentation" attribute added. This tells screen readers not to read the contents of this graphic.
2.  If your SVG file is used as meaningful content, ensure that the tag has a title="" attribute with a meaningful description.
3.  Ensure that your SVG file tag does not have an inline fill style on it. This will ensure that your SVG file will display correctly on the site.

---
## How To Replace Media
**IMPORTANT:** In order to replace a media item everywhere the original media item is referenced, you will need to make sure you have the same file name and extension for the replacement file. To get the file name and extension, navigate to the [Info tab](https://www.natptax.com/media/nmmhxirs/media-info-tab.png) of the media item.

1.  Navigate to the media item you wish to replace in the Media section.
2.  Below the image, click **Remove file(s)**. [View](https://www.natptax.com/media/5gehrkm5/media-properties.png)
3.  Click the **Upload** field to search or computer for your replacement media.Alternatively, you can drag and drop files into the **Upload** field.
4.  Click **Save**.
    
---
## How To Add Alt Text To Media
**NOTE:** Utilize the <a href="https://www.w3.org/WAI/tutorials/images/decision-tree/" target="_blank">alt decision tree</a> to help determine how to use the alt attribute on images.

### Adding Alt Text To Media In The Media Section
1.  Navigate to the media item you wish to add alt text to in the Media section.
2.  Below the image, add alt text in the **Alt Text** field. [View](https://www.natptax.com/media/5gehrkm5/media-properties.png)
3.  Click **Save**.

### Adding Alt Text To Media In The Rich Text Editor
1.  Within the rich text editor, click the **Media Picker** icon on the toolbar.
2.  Navigate to the media item you wish to add to your content.
3.  Click on the image.
4.  Add your alt text into the **Alternative text (optional)** field. [View](https://www.natptax.com/media/u5idvrmg/media-rich-text-editor.png)
5.  Click **Save**.

---
## How To Find Media Properties
1.  Navigate to the media item you wish to view properties for in the Media section.
2.  Below the image, the Width, Height, Size, Type, and Alt Text are listed. [View](https://www.natptax.com/media/5gehrkm5/media-properties.png)
3.  On the **Info** tab, the media file name is listed in the **Links** section. [View](https://www.natptax.com/media/nmmhxirs/media-info-tab.png)
