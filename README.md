# ReachInbox.AI: React Project

---

## Overview

This project is a React application written in TypeScript using figma file https://www.figma.com/file/uECxqvFhEx9dn4ZuO7wqmu/Reachinbox-Assignment?type=design&node-id=6-19154&mode=design&t=03bJH7Jr6FYF7VSR-0
and api documentation
https://documenter.getpostman.com/view/30630244/2sA2rCTMKr#433eb613-e405-4239-9e2d-f20485b31b27

---

## Installation

To install and run this project on your local machine, follow these steps:

1. **Clone Repository:**
   ```bash
   git clone https://github.com/punyakrit/Reachinbox-Assignment.git

   cd into project

   run `npm install`

   run `npm run dev`

   now open in browser 
   http://localhost:5173/

**Introduction:"Upon opening the app, you’re presented with two options: sign up with Google or create an account."

**Google Signup Flow:"I'll click the Google signup option. After choosing an email, the server generates a JWT token. This token is securely signed and encodes the user's details, ensuring safe communication."

**Passing JWT in URL:"The token is passed in the URL as ?token=your_jwt_token, which allows the server to authenticate the user with every request. After this, we land on the main page."

**Main Page Overview:"On the main page, there’s a sidebar button to view emails. Clicking it triggers an API call, with the JWT token ensuring secure data retrieval."

**Keyboard Shortcuts:"To streamline actions, I’ve added shortcuts: 'D' opens a confirmation window for email deletion, and 'R' opens a reply window."

**Light and Dark Mode Toggle:"Finally, there's a toggle button at the top for switching between light and dark modes, enhancing user customization."

**Conclusion:"And that’s the app—secure JWT-based authentication, responsive email management, efficient shortcuts, and customizable themes."
