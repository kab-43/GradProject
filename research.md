# LMS
## Summary
The fresh new idea, make a Learning Management System for university because the one we have is not it to say the least. This project aims to make an LMS as mobile application first using flutter for the mobile application (and maybe a website too?) with .net in the backend to deliver a highly performant and secure product to all students that actually helps you instead of feeling like an obscure piece of software that needs it's own manual.

## Problems with the current implementation
- The website has no real use case or application other than just filling paperwork for leaving much to be desired
- Lack of critical features such as storing subject material storage and assignment grading, etc...
- TLDR; if I go into a a specific section of the website I expect to press back to get back to the home page. The main buttons seem to be javascript functions if we understand correctly which make the back button ineffective which is counter-intuitive and results in an awful user experience.
- Relying on external components for functionality that's either too common to be not included (the subject registration) or too sensitive to be redirecting users to it (uploading student pictures)
- The design of the whole website is outdated and doesn't meet modern standards to say the least, here are some examples:
    - Lack of sorting/grouping options in many useful places
    - There doesn't need to be a specific box for something like uploading your picture, that should be under student data (just one quick example)
    - Adding an icon in the bottom left to change colors but having another icon for accessibilty setting when all this can be better grouped
    - The site needs to be reloaded every time you make a change such as paying tutition or registering subjects which shouldn't be a thing
- Localization, there is no excuse to directly translating ethical hacking to and I quote "القرصنة الاخلاقية"


## Features overview

### Intuitive Dashboard / Learning Hub



### Personalized Student Support

* The AI companion can access (with the user's consent of course) each student's courses, grades, schedule, and deadlines to provide them with personalized assistance.
* Available 24/7 with different locales and dialects.

### Fully Customizable AI companion

* Professors can instruct the AI companion to use specific refrences or use certain methods when explaining concepts first.
* Students also can control how the AI responds to them just like with any other AI.

### Course Management (doagain)

* Organized Content Library: Folders for lectures, PDFs, videos, recordings
* Version Control: Track material updates with "what's new" indicators
* Collaborative Notes: Students can upload/share notes (professor-moderated)
* Material Search: Search across all courses instantly
* Offline Access: Download materials for offline study (mobile app)
* Related Resources: AI suggests additional learning materials
* Annotation Tools: Highlight and annotate PDFs directly in-app

### Smart Session Alerts

* include the announcements bit here

### Calendar Integration

* Natural language commands: *“Add quiz to my calendar.”*
* Automatic deadline reminders through push notifications.

### Smart Notes

* Converts helpful chat conversations into organized study notes, auto-formatted with headings and key concepts.
* Students can save, export, and share these notes.

### Help Forums
* Allow the users to open different threads on different problems they face when studying
* Each student will have a banner signifying their contribution to the forums
* Professors and TAs will have their own badges to signify their position, it'll be like an admin helping with a problem

### Assignment Submission



### In-app Messaging

* add that adminstration can reach out to you through this not only teaching staff

### Academic progress tracker

* amino document here

### Student Services Center

* uni related stuff here (paying tutition and editing your data and such(

## Tech Stack
**Flutter** for the mobile application
**React** for the web interface
**.Net** for the backend
**SQL** for the database
**OpenAI GPT-40-mini** for the AI model


# TBD
anaything with "doagain" should be looked at again
do we use react or just flutter for everything
what areas do we feel are lacking to know who to talk to as our TA

