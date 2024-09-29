|<h3>**[xxx-5392] Missing Icons and Text for Delete Button and Selection Checkbox in "Uploaded Images" field** </h3>||
| :- | :- |
|**Status:**|Open|
|**Project:**|xxx|
|**Component/s:**|None |
|**Affects Version/s:**|None |
|**Fix Version/s:**|None |

|**Type:** |Bug |**Priority:** |Major |
| :- | :- | :- | :- |
|**Reporter:** |Aliaksei Borsuk |**Assignee:** |Unassigned |
|**Resolution:** |Unresolved |**Votes:** |0 |
|**Labels:** |Smoke |||
|**Remaining Estimate:**|Not Specified |||
|**Time Spent:**|Not Specified |||
|**Original Estimate:**|Not Specified |||
|**Environment:** |Windows 11, Google Chrome v.125.0.6422.176 <br>Windows 11, Microsoft Edge (Version 126.0.2592.61 (Official build) (64-bit)) <br>Windows 10, Microsoft Edge (Version 126.0.2592.61 (Official build) (64-bit)) Macos Monterey Version 12.6.2 <br>Windows 11, Mozilla Firefox (Version 127.0.1 (64-bit))|||

**Description**

**Project:** xxx
**Version: v1\_3\_001**
**Component:** Gallery
**Description:** The user interface should display a delete button and a checkbox for selecting an image. Instead, there are two buttons without icons or text.

**Preconditions**:

1. User is logged into the administration panel.

**Steps to reproduce:**

1. Navigate to Gallery tab.
1. Click "Create the album".
1. Select the "Date" in the date picker (pick the date from the appeared calendar).
1. Fill in the "Russian" text field (Cyrillic characters, numbers, special symbols -:,.!. length: 5-32).
1. Press "Save" button.
1. Click "Select image" checkbox.
1. Choose the images through the image upload area (format: JPEG, size: <3MB).


**AR:** Instead of a delete button and checkbox for image selection with an icons and text, there are two buttons displayed without icons or text.

**ER:** The user interface should display a delete button with an appropriate icon (e.g., trash bin icon) and text label. Checkbox should be clearly visible next to each image thumbnail, allowing users to select multiple images for uploading.

|<h3>**[xxx-5391] Incorrect date format displayed at the album creation window** </h3>||||
| :- | :- | :- | :- |
|**Status:**|Open|||
|**Project:**|xxx|||
|**Component/s:**|None |||
|**Affects Version/s:**|None |||
|**Fix Version/s:**|None |||
|**Type:** |Bug |**Priority:** |Medium |
|**Reporter:** |Aliaksei Borsuk |**Assignee:** |Unassigned |
|**Resolution:** |Unresolved |**Votes:** |0 |
|**Labels:** |Smoke |||
|**Remaining Estimate:**|Not Specified |||
|**Time Spent:**|Not Specified |||
|**Original Estimate:**|Not Specified |||
|**Environment:** |Windows 11, Microsoft Edge (Version 126.0.2592.61 (Official build) (64-bit)) Windows 10, Microsoft Edge (Version 126.0.2592.61 (Official build) (64-bit)) <br>Windows 11, Google Chrome v.125.0.6422.176|||
|**Attachments:** |date.png     |
| :- | :- |
|**Type:**|Functional |
|**Sprint:**|Sprint 1|


**Description**

**Precondition:** 

User is logged into administration panel.

**Steps to reproduce:** 
1\. Got to Administration Panel>Main Page>Gallery tab
2\. Click "Create the album"
3\. Fill in with valid data the "Date" field from the date picker (**DD.MM.YYYY** format)
4\. Pay attention to the fields displayed date format

**AR:** Incorrect date format displayed in the "Date" field at the album creation window.

**ER:** Date displayed in DD.MM.YYYY format in the "Date" field.

|<h3>**[xxx-5384] BE>Gallery>Album creation window: "Save" button remains active after click on it or if no changes were made** </h3>||
| :- | :- |
|**Status:**|Open|
|**Project:**|xxx|
|**Component/s:**|None |
|**Affects Version/s:**|None |
|**Fix Version/s:**|None |

|**Type:** |Bug |**Priority:** |Medium |
| :- | :- | :- | :- |
|**Reporter:** |Aliaksei Borsuk |**Assignee:** |Unassigned |
|**Resolution:** |Unresolved |**Votes:** |0 |
|**Labels:** |Smoke |||
|**Remaining Estimate:**|Not Specified |||
|**Time Spent:**|Not Specified |||
|**Original Estimate:**|Not Specified |||
|**Environment:** |Windows 11, Microsoft Edge (Version 126.0.2592.61 (Official build) (64-bit)) Windows 10, Microsoft Edge (Version 126.0.2592.61 (Official build) (64-bit)) <br>Windows 11, Google Chrome v.125.0.6422.176<br>Windows 11, Mozilla Firefox (Version 127.0.1 (64-bit))<br>Windows 11 Pro, Opera v.111.0.5168.25 |||
|**Attachments:** |3\.mp4     |
| :- | :- |
|**Type:**|Functional |
|**Sprint:**|Sprint 1|


**Description**

|<p>**Precondition:** <br>User is logged into administration panel.</p><p> </p><p>**Steps to reproduce:**</p><p>1\. Go to Administration Panel>Main Page>Gallery </p><p>2\. Click on the album from the list.</p><p>3\. Edit the field "Date" by selecting the date from the date picker (DD.MM.YYYY format)</p><p>4\. Click "Save" button</p><p>5\. Pay attention that after all the changes saved button "Save" still active</p><p> <br>**AR:** After click on "Save" button or if no changes were made, button "Save" remains active </p><p>**ER:** After click on "Save" button or if no changes were made the button is inactive </p><p> </p>|
| :- |

|<h3>**[xxx-5382] Impossibility to add news in English language when 'English' language is chosen.**  </h3>||
| :- | :- |
|**Status:**|Open|
|**Project:**|xxx|
|**Component/s:**|None |
|**Affects Version/s:**|None |
|**Fix Version/s:**|None |

|**Type:** |Bug |**Priority:** |Critical |
| :- | :- | :- | :- |
|**Reporter:** |Aliaksei Borsuk |**Assignee:** |Unassigned |
|**Resolution:** |Unresolved |**Votes:** |0 |
|**Labels:** |Smoke |||
|**Remaining Estimate:**|Not Specified |||
|**Time Spent:**|Not Specified |||
|**Original Estimate:**|Not Specified |||
|**Environment:** |Windows 11 Pro, Opera v.111.0.5168.25<br>Windows 11, Microsoft Edge v.126.0.2592.61<br>Windows 10, Microsoft Edge v.126.0.2592.61 <br>MacOs Monterey Version 12.6.2, Safari v.15.6.1|||

|**Attachments:** |Adding eng.mp4     |
| :- | :- |
|**Issue Links:** ||

|**Related To**||||
| :- | :- | :- | :- |
|relates to ...||||

|||
| :- | :- |
|**Type:**|Functional |

**Description:** User can't add news filling in the fields with valid data in English as the pop-up window 'Filling in Russian is required.' is displayed after clicking 'Save' button.
**Precondition:**

1. User is logged into administration panel.
1. Administrator is on the news list page (Administration panel - Volleyball - News).

**STR:**

1. Choose 'English' language from 'Language' dropdown.
1. Fill out the 'Title' text field (English letters, numbers, symbols, 5 -100)
1. Fill out the 'Description' text field (English letters, numbers, symbols, 15 -1000)
1. Fill out the 'Content' text field (English letters, numbers, symbols, 50 -100000)
1. Click 'Save' button.

**AR:** The pop-up window 'Filling in Russian is required.' is displayed.

**ER:** Added news is saved in the system and news list page is opened.
**Note:** Reproduces the same for mandatory/all fields using copy-paste as well; Chrome browser is the same.

|<h3>**[xxx-5380] BE>Gallery>Album creation window: the mandatory fields are not marked with the asterisk (\*)** </h3>||
| :- | :- |
|**Status:**|Open|
|**Project:**|xxx|
|**Component/s:**|None |
|**Affects Version/s:**|None |
|**Fix Version/s:**|None |

|**Type:** |Bug |**Priority:** |Low |
| :- | :- | :- | :- |
|**Reporter:** |Aliaksei Borsuk |**Assignee:** |Unassigned |
|**Resolution:** |Unresolved |**Votes:** |0 |
|**Labels:** |Smoke |||
|**Remaining Estimate:**|Not Specified |||
|**Time Spent:**|Not Specified |||
|**Original Estimate:**|Not Specified |||
|**Environment:** |Windows 11, Microsoft Edge (Version 126.0.2592.61 (Official build) (64-bit)) <br>Windows 10, Microsoft Edge (Version 126.0.2592.61 (Official build) (64-bit)) <br>Windows 11, Google Chrome v.125.0.6422.176<br>Windows 11, Mozilla Firefox (Version 127.0.1 (64-bit))<br>Windows 11 Pro, Opera v.111.0.5168.25|||

|**Attachments:** |1\.1.png     1.png     |
| :- | :- |
|**Type:**|Usability |
|**Sprint:**|Sprint 1|

**Description**

**Precondition:** 
User is logged into administration panel.

**Steps to reproduce:** 
1\. Got to Administration Panel>Main Page>Gallery tab
2\. Click "Create the album"
3\. Pay attention to the fields "Russian" and "Date"

**AR:** The mandatory fields "Russian" and "Date" of the album creation window are not marked with the asterisk \*

**ER:** The mandatory fields "Russian" and "Date" of the album creation window must be marked with the asterisk \*



|<h3>**[xxx-5475] Missing page navigation buttons 'next' (>) and 'previous'(<) on the 'All news' page**  </h3>||
| :- | :- |
|**Status:**|Open|
|**Project:**|xxx|
|**Component/s:**|None |
|**Affects Version/s:**|None |
|**Fix Version/s:**|None |

|**Type:** |Bug |**Priority:** |Medium |
| :- | :- | :- | :- |
|**Reporter:** |Aliaksei Borsuk |**Assignee:** |Unassigned |
|**Resolution:** |Unresolved |**Votes:** |0 |
|**Labels:** |xxx |||
|**Remaining Estimate:**|Not Specified |||
|**Time Spent:**|Not Specified |||
|**Original Estimate:**|Not Specified |||
|**Environment:** |Windows 11 Pro, Google Chrome v.125.0.6422.176<br>Windows 11 Pro, Opera v.111.0.5168.25|||

|**Attachments:** |not all buttons.png     |
| :- | :- |
|**Issue Links:** ||

|**Related To**||||
| :- | :- | :- | :- |
|relates to ...||||

|||
| :- | :- |
|**Type:**|Non-functional |

**Description**

**Description:** On the all news page where news items are listed at the bottom after opening page '2' not all navigation buttons are displayed.

**Preconditions:**
1\.'All news' page is open.
2\. At least 15 news items are added.

**Steps to reproduce:** 

1. Scroll down the page till you see page navigation buttons.
1. Click to open page '2'.

**AR:** Page navigation buttons '<<', '>>' are displayed. 

**ER:** Page navigation buttons '<<','<','>', '>>' are displayed. 
**Note:** The same reproduced in Chrome browser.

