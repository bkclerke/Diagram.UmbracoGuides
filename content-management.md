---
title: Content Management
layout: home
nav_order: 20
---

# Content Management

## How To Move A Node
{% include alert_note.html prefix="NOTE:" text="When moving pages, the Umbraco <strong>Redirect URL Management</strong> dashboard tracks the old and new paths and automatically creates a redirect." %}

1. In the Content section, click ••• next to the node and select **Move To**.
1. Choose where you want to move the page to in the tree structure.
1. Click **Choose** and a confirmation message will appear.

---

## How To Copy A Node
Re-use a node or a tree structure you have previously created by duplicating the parent node and its children to a different section within the site structure.

When you copy a parent node, all of its children pages are also copied by default. You can choose if you want to copy the child pages or not. You can also choose whether the links should be automatically updated or continue to link to the original pages.

1. In the Content section, click ••• next to the node and select **Duplicate To**.
1. Choose where you want to copy the page to in the tree structure.
1. Toggle **Relate to original** if you want to keep the links linked to the original page.
1. Toggle **Include descendants** if you want to copy the child nodes along with the parent node.
1. Click **Duplicate** and a confirmation message will appear. Your newly-duplicated node will be in an unpublished state by default.

---

## Recycle Bin
Upon deletion, nodes are moved to the Recycle Bin and are not deleted permanently.

The Recycle Bin is a separate tree list that can be found at the bottom of the section tree view. Clicking the arrow to the left of the Recycle Bin icon will reveal any nodes that have been deleted from the website.

In case you wish to restore the node, you can restore them from the Recycle Bin. You also have the option to move nodes out of the Recycle Bin to a new location or empty the Recycle Bin which permanently deletes all the items.

---

## How To Delete Nodes
{% include alert_warning.html prefix="IMPORTANT:" text="If you're deleting a page, this will result in a 404 for the previous URL. Please make sure that you check any linked items and create necessary redirects if applicable." %}

1. In the Content section, click ••• next to the node and select **Trash**.
1. If the node or any of its children have dependencies, they will be listed in the modal window so the references can be corrected before officially deleting.
1. Click **Trash** and a confirmation message will appear.

---

## How To Restore Nodes
1. Navigate to the node you wish to restore from the Recycle Bin, click ••• and select **Restore**.
1. In the confirmation window, click **Restore** and a confirmation will appear.

When a content node has been restored, it will be in an unpublished state. In order to display a restored content page on the website, navigate to the page and click **Save and publish**.

---

## How To Empty The Recycle Bin
If you are confident you no longer require any nodes in the Recycle Bin, you can permanently delete it. You can delete nodes one-by-one or empty the Recycle Bin as a whole.

{% include alert_warning.html prefix="IMPORTANT:" text="Deleting nodes from the Recycle Bin is permanent and you will not be able to undo this." %}

1. Click ••• next to the **Recycle Bin** node and select **Empty Recycle Bin**.
2. In the confirmation window, click **Empty Recycle Bin** and a confirmation will appear.

---

## Saving & Publishing Options
There are different options for saving and publishing nodes. The options vary depending on whether you’re still in the process of editing the content or have completed your edits and wish to publish your changes.

### Save And Preview
The **Save and preview** button allows you to save your changes and preview them before publishing to the live site. The preview feature shows how the page will look once it is published. NOTE: The Save and preview feature only saves your changes, it does not publish to the live site.

### Save
The **Save** button is used to save changes made to the node without officially publishing to the live site. The Save feature is especially useful if you are working on changes over a period of time as you can save your changes frequently to prevent losing any data.

### Save And Publish
The **Save and publish** button is used to publish any changes made to the node to the live website right away.

### Publish With Descendants
The **Publish with descendants** option allows you to publish the current node and all the content linked to it. Using this option, you can publish the current parent node and all of its child nodes, including previously-published and unpublished items.

1. Navigate to the page you want to publish.
1. Select the arrow next to the Save and Publish button.
1. Select **Publish with descendants**.
1. Toggle the option to **Include unpublished content items** if you wish to. This option includes all unpublished content items for the selected page and the available linked pages.

---

## Unpublishing Nodes
The Unpublish option allows you to unpublish a page if you do not want a page to be publicly visible and do not want to delete it.

### How To Unpublish A Node
{% include alert_warning.html prefix="IMPORTANT:" text="If you're unpublishing a page, this will result in a 404 for the previous URL. Please make sure that you check any linked items and create necessary redirects if applicable." %}

1. Navigate to the node you want to unpublish.
2. Click the menu arrow next to the **Save and publish** button and select **Unpublish**.
3. If the node or any of its children have dependencies, they will be listed in the modal window so the references can be corrected before officially unpublishing.
4. Click **Unpublish**.

---

## Schedule Publishing Options
The scheduling options allow you to set a date and time for when your page should be published or unpublished. With this option, you can continue working on your edits and the node will automatically publish/unpublish at the date and time it was scheduled.
 
{% include alert_note.html prefix="NOTE:" text="The schedule date/time is in your local time zone as a content editor." %}

### How To Set Up Scheduled Publishing
1. Navigate to the node you want to schedule for publish.
1. Click the menu arrow next to the **Save and publish** button and select **Schedule publish**.
1. Set the date and time in the **Publish at** at field.
1. Click **Schedule publish**.

### How To Set Up Scheduled Unpublishing
1. Navigate to the node you want to schedule to unpublish.
1. Click the menu arrow next to the **Save and publish** button and select **Schedule publish**.
1. Set the date and time in the **Unpublish at** at field.
1. Click **Schedule publish**.

---

## Audit Trail
On the **Info** tab of a node, you can find the audit trail in the **History** section. Here, you can get a quick overview of the actions performed on that node, by whom, when, and any additional comments. The history is useful to find out who made changes on a certain date.

---

## Version Management
Umbraco allows you to work with multiple versions of the same node. All previously-saved nodes are stored in a version history list.

### How To Compare Versions
1. Navigate to the node whose versions you wish to view.
1. Go to the **Info** tab.
1. Click the **Rollback** button in the **History** section.
1. Select a version you wish to compare with.
1. After selecting the version, a comparison of the current page with the version you selected will display. The text highlighted in red and striked-out will not appear in the selected version and the text highlighted in green means the text that will be added, should you choose to rollback to that version of the page.

### How To Rollback To A Previous Version
1. Navigate to the node whose versions you wish to view.
1. Go to the **Info** tab.
1. Click the **Rollback** button in the **History** section.
1. Select the version you wish to rollback to.
1. Click **Rollback** to proceed with the changes. Your content has now been rolled back to the selected version of the page and is saved as a **Draft** version.
1. To publish the draft, click **Save and publish**.
