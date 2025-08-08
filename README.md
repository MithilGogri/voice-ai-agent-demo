
# Voice AI Agent Demo

This repository hosts a demo web application showcasing a Voice AI Assistant powered by GPT-4o and 11Labs Text-to-Speech. The assistant can interact with users via voice and simulate actions such as arranging calls, scheduling meetings, and taking follow-ups using custom functions.

---

## Features

- Conversational AI assistant with a custom persona
- Voice synthesis using 11Labs voices
- Custom function calls for:
  - Arranging calls
  - Scheduling meetings
  - Taking follow-ups
- Responsive UI with background image and navigation
- Integration with VapiAI SDK for voice assistant functionality

---

## Demo

You can see the live demo here:  
[https://mithilgogri.github.io/voice-ai-agent-demo/](https://mithilgogri.github.io/voice-ai-agent-demo/)

---

## Project Structure

```
/index.html        - Main HTML file
/index.css         - Stylesheet
/assets/bg.jpg     - Background image
/src/index.js      - (Optional) JavaScript logic
```

---

## Setup & Usage

1. Clone this repository or download the files.

2. Update your API key and assistant configuration in `index.html`:

```js
const apiKey = "YOUR_VAPI_API_KEY";
const assistant = {
  // Your assistant config here
};
```

3. Serve the files locally (optional):

```bash
npx http-server
```

4. Or use GitHub Pages by pushing to your repository and enabling GitHub Pages on the main branch.

---

## Custom Functions

The assistant supports these functions:

- `ArrangeCall` — Arrange a call with a specified contact at a given time.
- `ScheduleMeeting` — Schedule a meeting with title, date, and time.
- `TakeFollowUp` — Take a follow-up action on a topic with a contact.

---

## Notes & Assumptions

- This demo uses VapiAI SDK for voice assistant integration.
- Function calls are simulated with alerts; you can extend them to integrate with backend services.
- Voice synthesis uses 11Labs voice with specified voice ID.
- The background image is stored in the `/assets` folder.
- The demo assumes an active internet connection to load external scripts and API calls.

---

## License

This project is for demonstration purposes and does not include any proprietary code. Use as you see fit.

---

## Author

Mithil Gogri  
[https://github.com/MithilGogri](https://github.com/MithilGogri)
