# Group Meetup Organizer

[My Notes](notes.md)

This web app will make it easy for users to not only organize group meetups, but also for people looking for a group to find groups in their area. Users can publish public groups that are open invitations, or they can create private groups in which they'll share the invitation with those they want to invite.


<!-- > [!NOTE]
>  This is a template for your startup application. You must modify this `README.md` file for each phase of your development. You only need to fill in the section for each deliverable when that deliverable is submitted in Canvas. Without completing the section for a deliverable, the TA will not know what to look for when grading your submission. Feel free to add additional information to each deliverable description, but make sure you at least have the list of rubric items and a description of what you did for each item.

> [!NOTE]
>  If you are not familiar with Markdown then you should review the [documentation](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) before continuing. -->

## 🚀 Specification Deliverable

<!-- > [!NOTE]
>  Fill in this sections as the submission artifact for this deliverable. You can refer to this [example](https://github.com/webprogramming260/startup-example/blob/main/README.md) for inspiration. -->

For this deliverable I did the following. I checked the box `[x]` and added a description for things I completed.

- [x] Proper use of Markdown - I have been practicing my markdown as I've never used it before:)
- [x] A concise and compelling elevator pitch - I wrote my elevator pitch (still working on catching an elevator with Steve Jobs)
- [x] Description of key features
- [x] Description of how you will use each technology
- [x] One or more rough sketches of your application. Images must be embedded in this file using Markdown image references.

### Elevator pitch

<!-- I love boardgames! Do you love boardgames? No? Oh. Well I've been having a difficult time finding others who want to play boardgames. Has this ever happened to you? You have an interest and you want to share this interest with someone else, but you struggle to find people with those same interests! I just wish there was an app where one could publish a meetup for a particular activity, and others in their area can see this event and meetup to find other people with this interest! It would be so simple to share information about a group bike ride, or an open board game night.  -->

Imagine an app that allows you to easily share info about group meetups in your area. Say you're hosting a D&D campaign and you need more players. Or you love riding bikes and you want to start a weekly group ride. Or perhaps you're wanting to find new hobbies and friends, but don't know where to start. This app would allow people to create groups that others in their area can view the meetup info and can show interest in particular activities in their area. It would make it so simple to find and make new friend groups with similar interests!

### Design

![Login image](images/startup.mock.login.png) ![Home image](images/startup.mock.home.png) ![Group image](images/startup.mock.group.png)

Users will create an account they can login with, ideally these accounts would be linked to their phone number so they can opt in on recieving text message reminders for events they've shown interest in or rsvp'd for. On the home page, users will see all nearby public events, and any private events they may be invited to. Users will be able to view the details of any group they select, such as the time and location of the next meetup, as well as a description of the group itself, the creator, and any other potentially important information

```mermaid
sequenceDiagram
    actor You
    actor Website
    You->>Website: Replace this with your design
```

### Key features

- Secure login over HTTPS
- Ability to view created groups
- Ability to create a new group
- Ability to join a created group
- Display of info about groups

### Technologies

I am going to use the required technologies in the following ways.

- **HTML** - Uses correct HTML structure for application. Four HTML pages. One for login, one for veiwing all nearby groups, another for veiwing a specific group, and one more for creating a new group.
- **CSS** - Application styling that looks good on different screen sizes, uses good whitespace, color choice and contrast.
- **React** - Allows for users to rsvp to events, login, view groups, create new groups, and other functionalities
- **Service** - calls on google maps' public api to access and share locations of groups and proximity to users.
- **DB/Login** - Store users and groups in database. Register and login users. Credentials securely stored in database. Can't rsvp unless authenticated.
- **WebSocket** - users will see new groups as they are created, and I hope to at somepoint enable a chatting feature for the individual groups.

## 🚀 AWS deliverable

For this deliverable I did the following. I checked the box `[x]` and I set up everyithing required for my website to be accessed securely by anyone in the world. yay!

- [x] **Server deployed and accessible with custom domain name** - [My server link](https://circleup.click).

## 🚀 HTML deliverable

For this deliverable I did the following. I checked the box `[x]` and added a description for things I completed.

- [x] **HTML pages** - I added HTML pages to my website.
- [x] **Proper HTML element usage** - I used a variety of proper HTML elements throughout my pages.
- [x] **Links** - I used links to navigate between pages.
- [x] **Text** - Most of my website's structure is composed of text.
- [x] **3rd party API placeholder** - I added a temporary link to google maps to demonstrate how my application will use google's services to share locations with users.
- [x] **Images** - I gave an example of how a circle might use an image to represent their group.
- [x] **Login placeholder** - I have boxes as placeholders for the user to enter login info.
- [x] **DB data placeholder** - I have filler info on the group page, which information would normally be stored in the database.
- [x] **WebSocket placeholder** - I have filler groups showing up on the main page, which websocket will allow for these groups to appear when a new one is created.

## 🚀 CSS deliverable

For this deliverable I did the following. I checked the box `[x]` and added a description for things I completed.

- [ ] **Header, footer, and main content body** - I did not complete this part of the deliverable.
- [ ] **Navigation elements** - I did not complete this part of the deliverable.
- [ ] **Responsive to window resizing** - I did not complete this part of the deliverable.
- [ ] **Application elements** - I did not complete this part of the deliverable.
- [ ] **Application text content** - I did not complete this part of the deliverable.
- [ ] **Application images** - I did not complete this part of the deliverable.

## 🚀 React part 1: Routing deliverable

For this deliverable I did the following. I checked the box `[x]` and added a description for things I completed.

- [ ] **Bundled using Vite** - I did not complete this part of the deliverable.
- [ ] **Components** - I did not complete this part of the deliverable.
- [ ] **Router** - Routing between login and voting components.

## 🚀 React part 2: Reactivity

For this deliverable I did the following. I checked the box `[x]` and added a description for things I completed.

- [ ] **All functionality implemented or mocked out** - I did not complete this part of the deliverable.
- [ ] **Hooks** - I did not complete this part of the deliverable.

## 🚀 Service deliverable

For this deliverable I did the following. I checked the box `[x]` and added a description for things I completed.

- [ ] **Node.js/Express HTTP service** - I did not complete this part of the deliverable.
- [ ] **Static middleware for frontend** - I did not complete this part of the deliverable.
- [ ] **Calls to third party endpoints** - I did not complete this part of the deliverable.
- [ ] **Backend service endpoints** - I did not complete this part of the deliverable.
- [ ] **Frontend calls service endpoints** - I did not complete this part of the deliverable.

## 🚀 DB/Login deliverable

For this deliverable I did the following. I checked the box `[x]` and added a description for things I completed.

- [ ] **User registration** - I did not complete this part of the deliverable.
- [ ] **User login and logout** - I did not complete this part of the deliverable.
- [ ] **Stores data in MongoDB** - I did not complete this part of the deliverable.
- [ ] **Stores credentials in MongoDB** - I did not complete this part of the deliverable.
- [ ] **Restricts functionality based on authentication** - I did not complete this part of the deliverable.

## 🚀 WebSocket deliverable

For this deliverable I did the following. I checked the box `[x]` and added a description for things I completed.

- [ ] **Backend listens for WebSocket connection** - I did not complete this part of the deliverable.
- [ ] **Frontend makes WebSocket connection** - I did not complete this part of the deliverable.
- [ ] **Data sent over WebSocket connection** - I did not complete this part of the deliverable.
- [ ] **WebSocket data displayed** - I did not complete this part of the deliverable.
- [ ] **Application is fully functional** - I did not complete this part of the deliverable.
