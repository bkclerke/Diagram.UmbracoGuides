---
title: Creating Content
layout: home
nav_order: 15
---

# Creating Content

## How To Create A New Page
In the **Content** section of the backoffice, a new page can be created in three different ways:

- In the left-side panel, click **+** next to the parent node you want to create your page beneath and select your new document type.
- In the left-side panel, click ••• next to the parent node you want to create your page beneath and click **Create**, then select your new document type.
- From the currently-active parent node, click the actions menu (•••) to the right of the node name and click **Create**, then select your new document type.

--- 

## Document Blueprints (Content Templates)
Document blueprints allow content editors to create a new node with certain properties pre-populated based on the document type and template selected.

### How To Create A Document Blueprint
1. Select a node in the content tree that you want to use as a baseline template.<br/>
   **TIP:** The type of content you are creating a template for can be found on the **Info** tab under **Document Type**.
2. Click the actions menu (•••) and select **Create Document Blueprint**.
4. Give your template a **Name** (ex: Department Landing Page).
5. Click **Create**.

### How To Use A Document Blueprint
Once you have created a document blueprint, you can use the template as a baseline to create new content nodes.

1. Click **+** to create a new node and select the document type.
2. Assuming the selected document type has at least document blueprint set up, it will ask you if you want to create a blank node or use an existing document blueprint.

When no document blueprints exist, a new blank node will be created by default.

### How To Edit A Document Blueprint
Content templates can only be edited or deleted by a system-level administrator as these are stored in Umbraco settings. Please reach out to your website administrator for any updates to content templates.

---

## How To Create For New Global Block
Global blocks are best used for content that will be reused across multiple places on the website. 

1. Navigate to the **Global Blocks** folder in the content tree.
1. Click **+** next to the parent block folder and click **Create**, then select your new block type.

---

## Best Practices for Creating Content

### Organize Your Content
It is important to keep your content tree organized with your content pages. This structure will automatically generate your main navigation and section navigation menus throughout the website, as well as determine what the URL structure will be for each page.

### Utilize Content Folders For Internal & Test Content Only
It is important to note that content should be organized with your pages first. Folders are **not** recommended for any content that is visible or searchable publicly on the website.

For example, creating a sandbox area would be a good use for a content folder. This folder should then be removed from crawling in the robots.txt and any child pages should be set to "Exclude From Search."

### URLs & Page Naming Conventions
Once you have saved and published a new page, a URL will be automatically generated for that page based on the name and path to the node in the Content Tree. Because of this, it is extremely important to make sure your content is structured well and try to avoid using very long page names as this will result in a long page URL. Umbraco will remove special characters from the URL that is generated for a page. It is also important to note that the page name will automatically be used as the H1 on your page. If your short page name is not descriptive enough, there is a Page Heading Override field available.
