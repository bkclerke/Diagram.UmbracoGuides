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
1.  To create a media folder, go to the Media section and click **+** next to the parent node you want to create a folder beneath.
2.  From the list of available media types, select **Folder**. [View](/images/media-create-action-menu.png)
3.  Enter the folder name.
4.  Click **Save**.

### How To Rename Folders
1.  Navigate to the Media section and select the applicable folder in the media tree.
2.  Update the folder name.
3.  Click **Save**.

---
## How To Delete Media
Media can be moved to the recycle bin in the same way content nodes can. Check out how to use the [Recycle Bin](./content-management.html#recycle-bin).

---
## How to Optimize Your Media
One of the biggest and most preventable issues that lead to slow page performance is uncompressed images. 

Before uploading an image:
1. Resize the image to the correct dimensions.
- The dimensions vary based on where the image will be used. Please refer to the recommended image sizes provided per feature.
- It's recommended to save/export photos from your image editor at 100% quality and let an image compressor handle all of the compression.
- For web display, images shouldn't exceed 72 DPI (it can be larger for downloads but not for just displaying images on the site).
2. Run the image through an image compression tool. Free compression tools to try out:
- <a href="https://shortpixel.com/online-image-compression" target="_blank">https://shortpixel.com/online-image-compression</a>
- <a href="https://tinyjpg.com/" target="_blank">https://tinyjpg.com/</a>
- <a href="https://compressor.io/compress" target="_blank">https://compressor.io/compress</a>
- <a href="https://imageresizer.com/" target="_blank">https://imageresizer.com/</a>
- <a href="https://compresspng.com/" target="_blank">https://compresspng.com/</a>
- <a href="https://compressjpeg.com/" target="_blank">https://compressjpeg.com/</a>
- RIOT (Windows app)
3. Rename your media files so they're clear, friendly, and utilize hyphens instead of spaces or other symbols. This is important for SEO and accessibility.

---
## How To Upload Media
In the Media section, you can upload media in three ways:
1.  Drag and drop your files in the main content area of the Media section. [View](/images/media-upload-section.png)
<br />**NOTE:** Make sure you have your folder selected first to keep your media organized.
1.  Click **+** next to **Media** and choose the media type, enter a name for your media item, and select the **Click to upload** field to choose a file type or drag the file into the upload field to upload the item. [View](/images/media-create-menu.png)
2.  Click the **Create** dropdown and choose the media type, enter a name for your media item, and select the **Click to upload** field to choose a file type or drag the file into the upload field to upload the item. [View](/images/media-create-action-menu.png)

---
## Optimizing Your SVG Files
When uploading SVG files to the Media section, it's important to check a few options in the SVG file itself to confirm that the SVG graphic will display correctly on the website.
1.  If your SVG file is used for decoration, ensure that the tag has the **role="presentation"** attribute added. This tells screen readers not to read the contents of this graphic.
2.  If your SVG file is used as meaningful content, ensure that the tag has a **title=""** attribute with a meaningful description.
3.  Ensure that your SVG file tag does not have an inline fill style on it. This will ensure that your SVG file will display correctly on the site.

---
## How To Replace Media
{% include alert_warning.html prefix="IMPORTANT:" text="In order to replace a media item everywhere the original media item is referenced, you will need to make sure you have the same file name and extension for the replacement file. To get the file name and extension, navigate to the <a href=\"/images/media-info-tab.png\">Info tab</a> of the media item." %}

1.  Navigate to the media item you wish to replace in the Media section.
2.  Below the image, click **Clear file(s)**. [View](/images/media-properties.png)
3.  Click the **Upload** field to search or computer for your replacement media.Alternatively, you can drag and drop files into the **Upload** field.
4.  Click **Save**.
    
---
## How To Add Alt Text To Media
{% include alert_warning.html prefix="IMPORTANT:" text="Utilize the <a href=\"https://www.w3.org/WAI/tutorials/images/decision-tree/\" target=\"_blank\">alt decision tree</a> to help determine how to use the alt attribute on images." %}

### Adding Alt Text To Media In The Media Section
1.  Navigate to the media item you wish to add alt text to in the Media section.
2.  Below the image, add alt text in the **Alt Text** field.
3.  Click **Save**.

### Adding Alt Text To Media In The Rich Text Editor
1.  Within the rich text editor, click the **Media Picker** icon on the toolbar.
2.  Navigate to the media item you wish to add to your content.
3.  Click on the image.
4.  Add your alt text into the **Alternative text (optional)** field. [View](/images/media-rich-text-editor.png)
5.  Click **Save**.

---
## How To Get The Direct Link & View Media Details
1.  Navigate to the media item you wish to view properties for in the Media section.
2.  Below the file, additional details are listed (width, height, file size, etc.). [View](/images/media-properties.png)
3.  On the **Info** tab, you can find all of the nodes on the site that reference the media item under the **Referenced By** section. The **Links** section also has the direct link to the media item. [View](/images/media-info-tab.png)
