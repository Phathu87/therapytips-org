# TherapyTips.org Project

## Overview
This project is developed for **TherapyTips.org**, consisting of three assignments that showcase the design and functionality of the website.

### Assignment 1: Website Design for TherapyTips.org
- **Objective**: Design a homepage, about page, and contact page with HTML and CSS.
- **Files**:
  - `index.html`: Homepage layout with content related to therapy tips.
  - `about.html`: Page detailing information about the therapy service.
  - `contact.html`: Contact form to reach the service provider.
  - `styles.css`: CSS file used for styling the pages.

  
The homepage includes a navigation bar, hero section, and sections for tips and services. The about page includes text content and team information, and the contact page includes a form with basic validation.

How it Works:
When the screen width is greater than 1199px, the .parent class will display the content in two columns.
When the screen width is less than 1200px, it will revert to the original single-column layout.

### Assignment 2: Paywall Implementation for TherapyTips.org
- **Objective**: Implement a paywall system to restrict access to certain content.
- **Overview**: This section implements a basic paywall, requiring users to subscribe for full access to premium content.
- **Files**:
  - `paywall.html`: Page with content behind the paywall, with a prompt to subscribe.
  - `paywall.css`: Styles for the paywall overlay and subscription section.
  - `paywall.js`: JavaScript to handle subscription logic and content display based on user access.

### Assignment 3: Scheduled Publish Feature for TherapyTips.org
- **Objective**: Implement a feature that allows writers to upload articles and specify a future publish date/time.
- **Overview**: This feature allows articles to be scheduled for future publishing, automating the content release process.
- **Frontend**:
  - `schedule_publish_feature.html`: Frontend interface where writers can upload articles and specify the publish time.
- **Backend**:
  - `schedule_publish_feature_backend.js`: Node.js script for scheduling the articles in the backend using a cron job to automatically publish them at the specified time.
  
The backend handles storing the article details and the scheduled publish time in a database, and a cron job checks periodically to publish the article once the scheduled time is reached.

### File Structure
The project structure is as follows:
therapytips-org/ ├── assets/ │ ├── images/ │ ├── js/ │ └── css/ ├── index.html ├── about.html ├── contact.html ├── schedule_publish_feature.html ├── schedule_publish_feature_backend.js └── README.md
