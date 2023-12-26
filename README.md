# LinkBot

## App Description:
- Simply, the application is about automating, managing, and simplifying LinkedIn actions and other communication platforms such as Skype, Outlook, Gmail, and WhatsApp.
- The main goal was to develop a desktop application that seamlessly streamlined targeted profile searches on LinkedIn, successfully capturing and storing profile information within our database. Integrated automated connection requests, email corresponding to specific filters, and multi-platform communication outreach (LinkedIn, Skype, Outlook, WhatsApp, Gmail) to optimize engagement with potential candidates.
- The overarching aim was to substantially minimize the time investment previously associated with manual execution in a user-friendly, interactive system resulting in enhanced efficiency and simplicity.

## App Frames/Phases:
### 1. Login Screen:
<img src="./Demo/1-Screenshot 2023-12-10 201504.png" width="750" height="600">

- In this screen, we can choose the accounts we want to sign in with, which we already saved in the system, and you can automatically log into all these accounts by just clicking on the "Login" button.
- We also have an "Add Account" button, which will take us to the Adding Account Screen.
- Finally, we have the **"Appearance Mode"**, in which we can change the application themes to white and dark.

### 2. Adding account Screen:
<img src="./Demo/2-Add Accounts Screenshot 2023-12-10 201551.png" width="750" height="600">

- This screen is used to add new accounts into the system to log into it in the future.

### 3. Main Action Screen:
<img src="./Demo/3-Main Actions Screenshot 2023-12-10 202441.png" width="750" height="600">

- LinkedIn Actions button: Takes us to LinkedIn Action Screen.
- Skype & Outlook section: After we specified and filtered emails, then copied to an excel file, we will be ready not to limit number of emails to send per click, choose the message template, and fill the Outlook Subject and we're ready to send a fully automatically mails into skype and Outlook in just one go.
- WhatsApp section: it's similar to Skype & Outlook fucntionality, except it's seperated to send direct-message into WhatsApp acording to specific phone numbers.
- Add Message Template button: Takes us to Message Template Screen.

### 4. LinkedIn Action Screen:
<img src="./Demo/4-Linkedin Actions Screenshot 2023-12-10 202637.png" width="750" height="600">

1. Search for Profiles section: This section is responsible in automatically searching for new or existing profiles on LinkedIn, so we can simply insert the Search Term, Location, and the Connection Degree if needed, from now u will have two options:
  - Start Searching button: It will loop over all search results pages, and save all these search results into our database to later use in fully profile scraping "Scraping Profiles section" or any other use (So if the search results got 1000 profiles, this action will save them all).
  - Scrape Current Search Page button: After filling the cells before correctly, and "Manually" go to the search results, by clicking into this button, it will scrape and save just shown search result page (Will save just the shown 10 profiles or whatever in that exact page).

2. Scraping Profiles section: Now it's time to fully scrape profiles which we got from the search results in the previews step. We can limit how much profiles to scrape at once, then we can use:
  - Start Scraping Profiles button: which will loop over profiles limit, visit each profile, and scrape full profile information to our database.
  - Scrape Current Profile button: Used to scrape a manually opened profile information.

3. Send Connections section: After the previews two steps, we now have multiple profiles in our database, which we can do some filtrations under certain criteria, specify the profiles URL, and we're ready to go
  - Start Sending Connections button: It will start directly send connection requests to these limited profiles with a certain message template "which will fit each account information as we will explain more in the next screen".
  - Re-send Connections to withdrew profs button: It will send connection requests to profiles which we withdrew since over 2 weeks ago "Which after we withdrew them, in the Other Action section".

4. Re-Messaging section: This section is the most important and complicated part, we use this section to automatically re-message profiles whose connected but didn't respond, or to direct-message certain profiles.
  - Re-message Non-responded Profiles button: Used to re-message profiles whose connected but didn't respond within a period of time, which their last message contains a Special Char "To specify and filter more profiles which we will respond too".
  - Start LinkedIn DM button: Is used to send direct-message to specific profiles on LinkedIn.

5. Other Actions section: This section contains the rest of actions that we can do in LinkedIn.
  - Withdrew Non-connected Profiles button: Is used to withdrew profiles whose didn't accept our connection request from or more than the specific period "The default is from or more than 2 weeks ago".
  - Update Connections List button: In the first use, it will save our all connection list into the database, after, it will just update and save just new connected profiles.

### 5. Message Template Screen:
<img src="./Demo/5-Adding Message temp Screenshot 2023-12-10 202534.png" width="750" height="600">

- last but not least, this Screen is used to add/edit/delete message templates.

## Demo Video:
- And finally here's a demo video to show the application in action:

<video src="./Demo/LinkBot_Demo.mp4" width="750" height="600">
