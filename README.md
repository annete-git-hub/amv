# Chat with Bubbles

A lightweight, browser-based chatbot interface built with HTML, CSS, and vanilla JavaScript.
The project focuses on delivering a polished user experience through modern UI design, smooth animations, and responsive interaction patterns.

---

## Overview

**Bubbly Chat Bot** is a front-end web application that simulates a conversational interface using rule-based logic. It is designed as a clean, self-contained project with no external dependencies or frameworks, making it ideal for learning, prototyping, or UI experimentation.

---

## Key Features

* **Modern User Interface**

  * Gradient-based design system
  * Animated decorative elements
  * Responsive and accessible layout

* **Interactive Messaging System**

  * Real-time message rendering
  * Distinct user and bot message styling
  * Automatic scroll management

* **Typing Indicator**

  * Visual feedback during bot response delay
  * Animated indicator for improved UX

* **Rule-Based Response Engine**

  * Pattern matching using regular expressions
  * Predefined conversational intents (greetings, help, emotions, etc.)
  * Randomized responses for selected categories

* **Session Persistence**

  * Chat history stored using `sessionStorage`
  * State retained during active browser session

* **Emoji Input Support**

  * Clickable emoji toolbar for quick message composition

---

## Technology Stack

| Layer     | Technology                            |
| --------- | ------------------------------------- |
| Structure | HTML5                                 |
| Styling   | CSS3 (Flexbox, animations, gradients) |
| Logic     | Vanilla JavaScript                    |
| Storage   | Web Storage API (`sessionStorage`)    |

---

## Project Structure

```
bubbly-chat-bot/
│
├── index.html     # Main application (UI + logic)
└── README.md      # Project documentation
```

---

## Getting Started

### Prerequisites

No dependencies or build tools are required.

### Installation

Clone the repository:

```bash
git clone https://github.com/your-username/bubbly-chat-bot.git
```

Navigate to the project directory:

```bash
cd bubbly-chat-bot
```

### Usage

Open the application in your browser:

```bash
start index.html
```

Alternatively, open the file manually by double-clicking `index.html`.

---

## Application Logic

The chatbot operates on a **rule-based system** using regular expressions to match user input against predefined patterns.

Example:

```javascript
{ 
  pattern: /\b(hi|hello|hey)\b/i, 
  reply: "Hello! 👋 How can I help you today?" 
}
```

If no pattern is matched, the system returns a fallback response selected at random.

---

## Limitations

* No backend or server-side processing
* No natural language understanding beyond pattern matching
* No persistent storage beyond the current browser session
* Limited contextual awareness between messages

---

## Roadmap

Potential enhancements for future development:

* Integration with AI APIs (e.g., OpenAI) for dynamic responses
* Persistent storage using a database or local storage
* Enhanced conversational context and memory
* Message typing animation (character-by-character)
* Dark mode and theming support
* Progressive Web App (PWA) capabilities

---

## Contributing

Contributions are welcome. To contribute:

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Open a pull request

Please ensure code is clean, documented, and consistent with the existing style.

---

## License

This project is licensed under the MIT License.
See the LICENSE file for more information.

---

## Author

Developed as a front-end UI/UX and JavaScript demonstration project.

---

## Acknowledgements

* Google Fonts (Nunito)
* Inspiration from modern messaging applications
