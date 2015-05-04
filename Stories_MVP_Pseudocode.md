<!-- Stories_MVP_Pseudocode.md -->

STORIES, MVP, & PSEUDOCODE
==========================================================================

### User Stories
1. Ability to create a private house
2. Ability to authenticate user
  - Google+
3. Ability to invite other users to their house
  - Housemates will receive invitation through email
4. Payment feature
  - Make payment
  - Ask for payment
  - Bill splitting
5. History feature
  - Payment history
  - Chore history
  - Activity history
6. Has three different message types
  - Task
  - Notification
  - Activity
7. Ability to send all kinds of messages to the house
8. Ability to read messages addressed to the house
  - All messages are shown by default
  - Messages appearing can be filtered by type
9. Ability to delete messages
10. Unread messages will be marked
11. Ability to track electric and utility usage
  - PG&E API



### MVP
- Login with Google+
  - Authentication
- Create house
- Invite housemates
- Tabs
  - _Home_
  - _Message_
  - _Payments_
  - _Housemates_
- See all of house messages
  - Unread messages are marked
  - Messages can be filtered by type
- Refresh the message board
- Send messages to the house
  - _Task_
    - A house chore that can be marked as done by a housemate
  - _Notif_
    - A notification/message to the house
  - _Activity_
    - An event that the house should be aware of and is invited to
- Payments can be made to any housemate
  - Venmo for secure payments
- History of each housemate can be viewed
  - Messages sent
  - Tasks complete
  - Activities commited to



### Pseudocode
###### TECHNOLOGIES:
- Structure
  - Ruby on Rails
  - ActiveRecord
  - Rails API
- View, Styling, Animations, and Transitions
  - Ionic Mobile Framework
  - AngularJS
  - HTML5
  - CSS3
- Behavior
  - JavaScript
  - jQuery
- Architecture
  - Decoupled
- Authentication
  - Auth0
  - Google+ API
- Secure Payments
  - Venmo API



###### PROCESS:
- Whiteboard goals
  - Turn into User Stories
  - Decide on MVP
- UX workflow
- Wireframe
- Deep dive into technologies
  - Ensure that any tech used is necessary
- Mobile-first design
- Responsive design
- Keep solid Git workflow
