---
title: Creating Content
layout: home
nav_order: 15
---

# Creating Content

## How To Create A New Page
You can create new pages in three ways:

1. Right-click on the parent node that you want to create a new page underneath, click **Create** in the menu, and select your new page.
1. Hover over the parent node, click ••• to open the create menu quickly, and select your new page.
1. From the currently active parent page, click the **Actions** menu, click Create and select your new page.

When no content templates exist, Umbraco will create a new node based on a blank template.

--- 

## Content Templates
Content Templates allows a content editor to create a blueprint for new content nodes based on an existing node.

### How To Create A Content Template
1. Select a node from the **Content** tree.
   **NOTE:** The type of content you are creating a template for can be found on the **Info** tab under **Document Type**.
2. Right-click on the node and click **Create Content Template**.
3. Alternatively, select the **Actions** dropdown on the node and click **Create Content Template**.
4. Give your template a **Name**.
5. Click the **Create** button and if the creation was successful, you will see a success notification.

### How To Use A Content Template
Once you have created a content template, you can use the template to create new content nodes.

1. To use a content template, right-click the **Content** tree and select **Create**.
1. When you click a document type that has content templates, Umbraco lets you choose to create a new node based on a content template or a blank one.

### How To Edit A Content Template
Content templates can only be edited or deleted by a system-level administrator as these are stored in Umbraco settings. Please reach out to your website administrator for any updates to content templates.

---

## How To Create A New Block
Global blocks are best used for content that will exist in multiple places on the website. 

1. Navigate to the **Global Blocks** folder in the Content Tree.
1. Right-click on the parent node that you want to create a new block underneath, click **Create** in the menu, and select your new block.
Alternatively, you can hover over a block folder, click ••• to open the create menu quickly, and select your new block.

---

## Best Practices for Creating Content

### How To Organize Your Content
It is important to keep your Content tree organized with your content pages. This structure will automatically generate your main navigation and section navigation menus throughout the website.

### How To Utilize Content Folders
It is important to note that content should be organized with your pages first. Utilizing Content Folders is **not** recommended for any content that needs to be searched within the website.

For example, creating a sandbox area would be a good use for a content folder. This folder should then be removed from crawling in the robots.txt and any child pages should be set to "Exclude From Search".

### URLs & Page Naming Conventions
Once you have saved and published a new page, a URL will be automatically generated for that page based on the name and path to the node in the Content Tree. Because of this, it is extremely important to make sure your content is structured well and try to avoid using very long page names as this will result in a long page URL. Umbraco will remove special characters from the URL that is generated for a page. It is also important to note that the page name will automatically be used as the H1 on your page. If your short page name is not descriptive enough, there is a Page Heading Override field available.