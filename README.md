# LinkBot

## Contents:
- [App Description](https://github.com/MostaAshour/LinkBot/tree/main?tab=readme-ov-file#app-description)
- [App Frames/Phases:](https://github.com/MostaAshour/LinkBot/tree/main?tab=readme-ov-file#app-framesphases)
  - [1. Login Screen](https://github.com/MostaAshour/LinkBot/tree/main?tab=readme-ov-file#1-login-screen)
  - [2. Adding Account Screen](https://github.com/MostaAshour/LinkBot/tree/main?tab=readme-ov-file#2-adding-account-screen)
  - [3. Main Action Screen](https://github.com/MostaAshour/LinkBot/tree/main?tab=readme-ov-file#3-main-action-screen)
  - [4. LinkedIn Action Screen](https://github.com/MostaAshour/LinkBot/tree/main?tab=readme-ov-file#4-linkedin-action-screen)
  - [5. Message Template Screen](https://github.com/MostaAshour/LinkBot/tree/main?tab=readme-ov-file#5-message-template-screen)
- [Demo Video](https://github.com/MostaAshour/LinkBot/tree/main?tab=readme-ov-file#demo-video)
- [Requirements](https://github.com/MostaAshour/LinkBot/tree/main?tab=readme-ov-file#requirements)
- [Contacts](https://github.com/MostaAshour/LinkBot?tab=readme-ov-file#contacts)

## App Description:
- The LinkBot application automates, manages, and simplifies actions on LinkedIn and other communication platforms like Skype, Outlook, Gmail, and WhatsApp. It is a desktop application designed to streamline targeted profile searches on LinkedIn, capture and store profile information in a database, and facilitate automated connection requests, email correspondence, and multi-platform communication outreach. The goal is to enhance efficiency and simplicity by minimizing the time investment previously required for manual execution.

## App Frames/Phases:
### 1. Login Screen:
<img src="./Demo/1-Screenshot 2023-12-10 201504.png" width="750" height="600">

- Users can choose the accounts they want to sign in with, which are saved in the system. By clicking the "Login" button, they can automatically log into all these accounts.
- There is an "Add Account" button that takes users to the Adding Account Screen.
- Users can switch between different themes (white and dark) using the "Appearance Mode" feature.

### 2. Adding account Screen:
<img src="./Demo/2-Add Accounts Screenshot 2023-12-10 201551.png" width="750" height="600">

- This screen allows users to add new accounts to the system for future login.

### 3. Main Action Screen:
<img src="./Demo/3-Main Actions Screenshot 2023-12-10 202441.png" width="750" height="600">

- LinkedIn Actions button: Takes users to the LinkedIn Action Screen.
- Skype & Outlook section: Users can specify and filter emails, copy them to an Excel file, and send automated emails to Skype and Outlook. They can customize the number of emails sent per click, choose message templates, and fill in the Outlook Subject to optimize communication.
- WhatsApp section: Similar to Skype & Outlook functionality, users can send direct messages to specific phone numbers on WhatsApp.
- Add Message Template button: Takes users to the Message Template Screen.

### 4. LinkedIn Action Screen:
<img src="./Demo/4-Linkedin Actions Screenshot 2023-12-10 202637.png" width="750" height="600">

1. Search for Profiles section: This section automatically searches for new or existing profiles on LinkedIn. Users can insert the search term, location, and connection degree if necessary. They have two options:
    - Start Searching button: It loops over all search result pages and saves the profiles into the database for later use, such as full profile scraping or other purposes.
    - Scrape Current Search Page button: By clicking this button, users can manually go to the search results page and save the profiles shown on that page.
    - Scraping Profiles section: Users can fully scrape the profiles obtained from the search results. They can set a limit on the number of profiles to scrape at once. The available options are:

2. Start Scraping Profiles button: It loops over the specified profile limit, visits each profile, and scrapes full profile information into the database.
    - Scrape Current Profile button: Users can manually scrape the information from the currently opened profile.
    - Send Connections section: Users can apply filters to the profiles in the database and specify the profile URL for sending connection requests.

3. Start Sending Connections button: It sends connection requests to the selected profiles using a predefined message template that can be customized for each account.
    - Re-send Connections to withdrew profiles button: It sends connection requests to profiles that were previously withdrawn, with a time limit of 2 weeks.
    - Re-Messaging section: This section allows users to automatically re-message profiles who connected but didn't respond, or send direct messages to specific profiles.

4. Re-message Non-responded Profiles button: Users can re-message profiles who connected but didn't respond within a specified period, with the option to filter based on the content of their last message.
    - Start LinkedIn DM button: Users can send direct messages to specific profiles on LinkedIn.
  
5. Other Actions section: This section includes additional actions that can be performed on LinkedIn.
    - Withdrew Non-connected Profiles button: Users can withdraw connection requests sent to profiles that haven't been accepted after a specific period (default: 2 weeks).
    - Update Connections List button: In the first use, it saves all connection lists into the database. Afterward, it updates and saves only newly connected profiles.

### 5. Message Template Screen:
<img src="./Demo/5-Adding Message temp Screenshot 2023-12-10 202534.png" width="750" height="600">

- This screen allows users to add, edit, and delete message templates.

## Demo Video:
- Here's a demo video to showcasing the application in action: [Video link](https://drive.google.com/file/d/1DLMQa2ZaJA83TNGOPHBrLjsrCfdJNE6t/view?usp=sharing)

## Requirements:
The LinkBot application is developed using Python 3.9.0. Below are the required packages and dependencies:
- Python 3.9.0: The programming language used for developing the application.
  
Packages:
- numpy==1.21.6
- pandas==1.3.5
- pytz==2022.7.1
- urllib3==1.26.14
- selenium==3.141.0
- customtkinter==5.1.2
- chromedriver-autoinstaller==0.4.0

You can find the complete list of required packages and their versions in the file [here](requirements.txt). We have to ensure that these packages are installed in our Python environment before running the application.

## Contacts:
I would be delighted to connect with you! Please feel free to reach out to me via LinkedIn or email for any inquiries or discussions.

LinkedIn: [Mosta Ashour](https://www.linkedin.com/in/mosta-ashour/)
Email: mostaomg@gmail.com

Thank you and have a wonderful day! 😊
