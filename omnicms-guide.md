# OmniCMS Quick Reference Guide

**This guide is for internal users of OmniCMS and is based on the most frequenly asked questions.**

---


## Concept
### Summary
_In this section provide a brief summary of the conceptual information you plan to provide. This should allow the users to understand what they will find on this page._
### Detailed Overview
_In this section provide the details related to your conceptual information. This should allow the users to deep dive into understanding the concept. Use appropriate graphic or video files to explain the details._
### Example
_In this section provide an example of the conceptual information you plan to provide. A specific example often helps your users better understand a concept._




**The Difference Between Sections and Folders**

 "Folders" are for organizing (content), "sections" are subsites with a new left side navigation. 

- A 'section' contains webpages. 
Visit the [OmniCMS Support Site](https://support.moderncampus.com/learn-omni-cms/sections-folders/) to learn how to create a section and a folder.

- A 'folder' can contain documents or images. 
  (Example: /images/yourdirectory/image.jpg)

---

## Managing Pages

**Log in to Edit a Page:**

To log in to OmniCMS, navigate to the webpage you want to edit and click the copyright (©) symbol in the footer.

---

## Navigate to the Staging Server

To access the Staging server:

 1. Click the **Content** drop-down menu in the top-right corner.
 2. Select **Pages**

![Screen shot of content menu with page highlighted](https://raw.githubusercontent.com/cdpearsontx/cms-quick-reference/refs/heads/main/images/omnicms-content-dropdown-new-page.jpg)
 
3. Select "Staging Server" from the list.




---

## Creating a New Section Step by Step (website/subsite) 

1. In the upper right portion of the screen, click "New".
2. Select "New Section" in the drop down menu.
   
<img src="https://raw.githubusercontent.com/cdpearsontx/cms-quick-reference/refs/heads/main/images/omnicms-new-section.JPG" width="400" alt="new section screehshot">

3. Fill out the form fields. (**Note: filename must be lowercase**)

<img class="img-spacing" src="https://raw.githubusercontent.com/cdpearsontx/cms-quick-reference/refs/heads/main/images/omnicms-new-section-form%3Dfields.jpg" width="500" alt="screenshot of new section fields">

---

## Page Management

**Creating a New Page**

To start creating a new page:
1. Select the **Content** drop-down menu at the top of the screen.
<img src="https://raw.githubusercontent.com/cdpearsontx/cms-quick-reference/refs/heads/main/images/omnicms-content-dropdown-new-page.jpg" width="500" alt="screenshot of content drop down with Pages highlighted">


**Rename a webpage:**

![OmniCMS File Rename](https://raw.githubusercontent.com/cdpearsontx/cms-quick-reference/refs/heads/main/images/omnicms-file-rename.jpg)

1. Locate the .pcf file you want to rename in the file list.
2. Click the three-dot menu on the right side of the file row.
3. In the drop down menu, select **Rename** (the first option).
4. Enter the new file name.
5. Hit the 'enter' key to confirm the change.
   
---

**Deleting a Page from the Live Server**

To delete a page from the live server, recyle the page from the staging server. This will remove the page from the live server.


1. **Find the Page to Remove**
  - Locate the webpage you want to delete.

2. **Recycle the Page**

Click the [Options Dropdown] next to the page title.
Select "Recycle" from the menu.
Confirmation

The page is now removed from the live server automatically.

**How to Recover a Deleted Page or File**

1. Select the **Content** drop down menu at top of the OmniCMS screen.
<img src="https://raw.githubusercontent.com/cdpearsontx/cms-quick-reference/refs/heads/main/images/omnicms-content-dropdown.jpg" alt="screenshot of the drop down menu for Content" with="600">
2. From the Content drop-down, select **Recycle Bin**
<img src="https://raw.githubusercontent.com/cdpearsontx/cms-quick-reference/refs/heads/main/images/omnicms-content-menu-recyle-bin.jpg" alt="screenshot of the Content menu highlighting the Recycle Bin option" with="600">
3. To locate you deleted file, you can:
  - Search using a keyword in the filter.
  - Click on any of the three sorting categories:  
    - Original Location
    - Recycle by (User)' 
    - 'Recyle Date'

<img src="https://raw.githubusercontent.com/cdpearsontx/cms-quick-reference/refs/heads/main/images/omnicms-recyle-bin-filter-sort.JPG" alt="screenshot of 
the Recycle bin filder and sorting categories" with="600">


## Images

- Images should be 1mb or under.
- Add 'img-fluid' class to jpg and png files
- To ensure a banner or 'hero' image is full-width and responsive, add ``"width="100%"`` to the ``'img src'``
Example:
 ```<img src="/images/directory/image.jpg" alt="descriptive text" class="img-fluid" width="100%">```
