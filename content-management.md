---
title: Content Management
layout: home
nav_order: 20
---

# Content Management

## How To Move A Page
**NOTE:** When moving pages, the Umbraco **Redirect URL Management** dashboard will track the new path and automatically create a redirect if enabled.

1. From the Content section, right-click on the page and click **Move**.
1. Alternatively, you can click ••• next to the parent node and select **Do something else** and click **Move**.
1. A window appears next to the section tree. Here, you can choose where you want to move the page in the tree structure.
1. Click **Move**.
1. A confirmation message appears. Click **OK** to dismiss the confirmation message.


## How To Copy A Page
Re-use a page or a tree structure you have previously created by copying the parent page and its child pages to a different section within the site structure.

When you copy a parent page all of its child pages are also copied, by default. You can choose if you want to copy the child pages or not. You can also choose whether the links should be automatically updated or continue to link to the original pages.

1. Go to the Content section.
1. Right-click on the page and click **Copy**.
1. Alternatively, you can click ••• next to the parent node and select **Do something else** and click **Copy**.
1. A window appears next to the section tree. Here, you can choose where you want to copy the page in the tree structure.
1. Toggle **Relate to original** if you want to keep the links linked to the original page.
1. Toggle **Include descendants** if you want to copy the child pages along with the parent page.
1. Click **Copy**.
1. A confirmation message appears. Click **OK** to dismiss the confirmation message.

## Recycle Bin
Upon deletion, nodes are moved to the Recycle Bin and are not deleted permanently.

The Recycle Bin is a separate tree list that can be found at the bottom of the section tree view. Clicking the arrow to the left of the Recycle Bin icon will reveal any nodes that have been deleted from the website.

In case you wish to restore the node, you can restore them from the Recycle Bin. You also have the option to move nodes out of the Recycle Bin to a new location or empty the Recycle Bin which permanently deletes all the items.

## How To Delete Nodes
**IMPORTANT:** This action will result in a 404 for the previous node URL. Please make sure that you check any linked items and create necessary redirects.

1. Go to **Content**.
1. Right-click the node you wish to delete and select **Delete**. [View](/images/delete-node-tree-menu.png)
1. Alternatively, click **Actions** in the top-right corner of the screen and select **Delete**. [View](images/delete-node-action-menu.png)
1. A window appears next to the section tree confirming if you want to delete the node.
1. Click **OK**.
1. A confirmation message appears. Click **OK** to dismiss the confirmation message.

## How To Restore Nodes
1. Right-click the node you wish to restore from the Recycle Bin and select **Restore**. Alternatively, click ••• next to the node in the Recycle Bin and select **Restore**. [View](images/recycle-bin-restore-menu.png)
1. You can also click **Actions** in the top-right corner of the screen and select **Restore**.
1. A window appears next to the section tree confirming if you want to restore the node.
1. Click **Restore**.
1. A confirmation message appears. Click **OK** to dismiss the confirmation message.

When a content node has been restored, it will be in an unpublished state. In order to display a restored content page on the website, navigate to the page and click **Save and publish**.

## How To Empty The Recycle Bin
If you are confident you no longer require any nodes in the Recycle Bin, you can permanently delete it. You can delete nodes one by one or empty the Recycle Bin in one go.

**IMPORTANT:** Deleting nodes from the Recycle Bin is permanent and you will not be able to undo this.

1. Right-click the **Recycle Bin** and select **Empty recycle bin**. Alternatively, click ••• next to the **Recycle Bin** and select **Empty recycle bin**. [View](images/recycle-bin-menu.png)
1. A window appears next to the section tree confirming if you want to empty the recycle bin.
1. Click **OK**.

## Saving and Publishing Options
There are different options for saving and publishing pages. The options vary depending on whether you’re still in the process of editing the page or have completed your edits and wish to publish your changes.

### Save and Preview
The **Save and preview** button allows you to save your changes and preview them before publishing the changes to the live site. The **Preview** feature shows you how the page will look once it is published. This **Save and preview** feature only saves your page and does not publish your content to the live site.

### Save
The **Save** button is used for saving the page without publishing the changes to the live site. The **Save** feature is especially useful if you are working on changes over a period of time as you can save your changes frequently to prevent losing any data.

### Save and Publish
The **Save and publish** button is used to publish a previously saved page to the live website or to publish a page without previewing it. The **Save and publish** feature will save and publish the page to your live website.

### Publish with Descendants
The **Publish with descendants** button allows you to publish the current page and all the content linked to this page to the live site. Using this option, you can publish the current parent page and its child nodes, previously published, and unpublished content items.

To publish the node with descendants, follow these steps:

1. Navigate to the page you want to publish.
1. Select the **arrow** next to the Save and Publish button.
1. Select **Publish with descendants**.
1. Toggle the option to **Include unpublished content items** if you wish to. This option includes all unpublished content items for the selected page and the available linked pages.

## Unpublishing Pages
The Unpublish button allows you to unpublish a page if you do not want a page to be publicly visible and do not want to delete it.

### How To Unpublish A Page
**IMPORTANT:** This action will result in a 404 for the previous node URL. Please make sure that you check any linked items and create necessary redirects.

1. Navigate to the page you want to unpublish.
1. Select the **arrow** next to the Save and Publish button.
1. Select **Unpublish**.

## Schedule Publishing Options
The Schedule button allows you to set a time and a date for when your page should be published. With this option, you can continue working on your edits and the site will automatically be published at the time and date it was scheduled to.

**NOTE:** The schedule date time is in your time zone as a content editor.

### How To Set Up Scheduled Publishing
1. Navigate to the page you want to publish.
1. Select the **arrow** next to the Save and publish button.
1. Select **Schedule**.
1. In the **Scheduled Publishing** window, set the date and time in the **Publish** at field.
1. Select Schedule.
1. You can also unpublish your page by setting the date and time using the **Schedule** feature.

### How To Set Up Scheduled Unpublishing
1. Navigate to the page you want to unpublish.
1. Select the **arrow** next to the Save and Publish button.
1. Select **Schedule**.
1. In the **Scheduled Publishing** window, set the date and time in the **Unpublish** at field.
1. Select **Schedule**.


## Audit Trail
Within the **Info** content app for pages you can find the **Audit Trail** in the **History** section. Here, you can get a quick overview of the actions performed on that node, by whom, when and any additional comments.

The Audit Trail is useful to find out who made changes on a certain date.

### How To View The Audit Trail
1. Go to the **Content** section.
1. Navigate to the page you wish to see the audit trail.
1. Go to the **Info** tab.

## Version Management
Umbraco allows you to work with multiple versions of the same page. All previously saved pages are stored in a version history list.

### How To Compare Versions
1. Navigate to the page whose versions you wish to view.
1. Go to the **Info** tab.
1. Click on the **Rollback** button in the **History** section.
1. The Rollback window opens. Select a version you wish to compare with.
1. After selecting the version, a comparison of the current page with the version you selected is displayed. The text highlighted in red and striked-out will not appear in the selected version and the text highlighted in green means the text that will be added, should you choose to rollback to that version of the page.

### How To Rollback To A Previous Version
1. Navigate to the page whose versions you wish to view.
1. Go to the **Info** tab.
1. Click on the **Rollback** button in the **History** section.
1. The Rollback window opens. Select a version of the page you wish to Rollback to.
1. Click **Rollback** to proceed with the changes. Your content has now been rolled back to the selected version of the page and is saved as a **Draft** version.
1. To publish the draft version, click **Save and publish**.