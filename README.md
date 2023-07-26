## Readme.txt - MyLeads Manager

This readme.txt provides an overview and usage instructions for the MyLeads Manager, a simple web application that allows users to save and manage leads.

### Description

The MyLeads Manager is a basic web application implemented using JavaScript that allows users to save and view a list of leads. The application utilizes the browser's local storage to store the leads, allowing the leads to persist even if the page is refreshed or the browser is closed.

### Features

1. **Save Leads**: Users can save leads by entering a URL in the input field and clicking the "Save Lead" button. The entered URL will be added to the list of leads and stored in the browser's local storage.

2. **View Leads**: The application displays the list of saved leads as clickable URLs. When users click on a lead, it will open in a new browser tab.

3. **Delete Leads**: Users can delete all the saved leads by double-clicking the "Delete Leads" button. This action will clear the local storage and reset the leads list.

4. **Save Current Tab as Lead**: By clicking the "Save Current Tab" button, users can quickly save the URL of the currently active tab in the browser.

### How to Use

1. Open the MyLeads Manager in your web browser.

2. To save a lead, enter the URL in the input field and click the "Save Lead" button.

3. To view the saved leads, scroll down to see the list of clickable URLs. Click on any URL to open it in a new tab.

4. To save the URL of the currently active tab, click the "Save Current Tab" button.

5. To delete all the saved leads, double-click the "Delete Leads" button. This action will clear the local storage and reset the leads list.

### Notes

- The MyLeads Manager uses the Chrome browser's extension API to save the URL of the currently active tab. Ensure that you are using Google Chrome and have the appropriate permissions to access the active tab.

- The leads will persist even after closing the browser or refreshing the page, as they are stored in the browser's local storage.

- The MyLeads Manager is a simple demonstration of local storage usage and lead management. For more advanced features and functionalities, additional development may be required.

- If you encounter any issues or have suggestions for improvement, feel free to report them in the repository's issue section.

Happy lead management!

https://main--leadsforchrome.netlify.app/
