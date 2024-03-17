# HuddleHub
HuddleHub is an Online Peer-to-Peer Group Video Chat Application that leverages WebRTC concepts. It offers a range of features - group video calling, group texting, screen sharing, and much more. One notable feature is the HuddleBot, which notifies all participants in the room whenever someone joins or leaves.

Live Link at : [Click Me!](https://huddlehub.onrender.com)

![Screenshot 2024-03-17 145338](https://github.com/sarthakvs/HuddleHub/assets/98168713/6cd13cd4-0623-412f-9624-5fdcfbf305d6)
![Screenshot 2024-03-17 151305](https://github.com/sarthakvs/HuddleHub/assets/98168713/878a9a10-7984-4182-89a9-9673cca3adbc)
![Screenshot 2024-03-17 151639](https://github.com/sarthakvs/HuddleHub/assets/98168713/7d72d4a5-1dcc-4069-8df2-692225d1a938)

# Features
  1. Platform supported : Web
  2. Group Video Calling: Engage in real-time video conversations with multiple participants simultaneously.
  3. Group Texting: Chat with other participants in the room via text messages.
  4. Screen Sharing: Share your screen with others in the room, allowing for collaborative viewing of presentations, documents, or other content.
  5. Responsive Design: Enjoy a user-friendly experience across various devices and screen sizes.
  6. HuddleBot Notifications: Receive notifications whenever someone joins or leaves the room, ensuring everyone stays informed.
  7. Easy Room Creation/Joining: Enter your name and select a room to join or create a new one effortlessly.
  8. Persistent Participation: Remain connected to the room and continue to hear and see what's happening even if you leave the tab or window open.
  9. Participant Management: View a list of participants in the room and pin/unpin individual streams for closer focus.

# How to Use
  1. Open the [HuddleHub](https://huddlehub.onrender.com) application.
  2. Enter your name in the designated field.
  3. Choose or create a room you want to join.

# Technologies Used
  HTML, CSS, JavaScript, Agora_RTC SDK, Agora_RTM SDK, Node, Express
  
# Limitations
  Same user name : same user name person can easily join the meeting and no admin who can remove users (To Do)
# How to Run Locally
  To install and run HuddleHub locally on your system, follow these steps:

  1. Clone the repository to your local machine
  2. Run `npm i` in the terminal in the root directory of the cloned repository to install dependencies.
  3. Create an account on agora.io and generate an app ID for your project.
  4. Update the `APP_ID` value in public/js/room_rtc.js.
  5. Run `node index.js` in the terminal.
