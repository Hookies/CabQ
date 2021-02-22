# CabQ MVP SCOPE
In this document we will define the MVP of the CabQ project, This will be the product that launches and is iterated upon in the future

## Front End
- Simple UI Taking advantage of an existing design library.
- Dark Mode by default.

### Venue Selection
- Simple list view or dropdown view
- Support Sydney arcades only

### Cabinet Selection
- List view of games, Name, image etc...

### Queue
- Users can join queues
  - User can join with a QR code
- Users can leave queues
- Users to vote to skip a queue position
  - Someone leaves etc...
  - Group vote to "move" the turn to someone else
- Normie button, Let a new player jump to the top of the queue. Vote etc.
- Users can vote if a session is over
  - Users can also mark their own session as completed
  - Estimate based off average time to play, Prompt users after the "Average" time is up
- See what user is currently playing on the cab your queued for.

### Arcade PSA / Announcements / Community hubs
- Game specific PSAs
- Game specific Announcements
- Location specific PSAs
- Location specific Announcements
- No chat/Forum on platform
  - Allow links to Discord/Forums/Image-boards etc...

### How to play
- Keep in mind, Content for phase 2

### User accounts
- Allow users to set their names
- Allow users to set their main games
- Allow users to link social platforms
- Bio

## Backend

### Authentication
- Allow email and Phone signup
- Authenticate via Cognito
- Allow Un-authed users / guests

### API
- GraphQL API
- Take advantage of the Serverless Framework
  - Lambda function
  - Cloudformation
  
