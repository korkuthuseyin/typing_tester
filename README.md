# Typing Tester App

A **Typing Tester** application built with **React**, **JavaScript**, and **CSS**. This app is designed to improve typing speed and accuracy by providing random paragraphs for practice. It tracks metrics such as **Words Per Minute (WPM)**, **Characters Per Minute (CPM)**, and mistakes.

---

## Features

- Random paragraph generation for typing practice.
- Tracks:
  - **Words Per Minute (WPM)**
  - **Characters Per Minute (CPM)**
  - **Number of mistakes**
- Real-time updates as you type.
- Clean and responsive UI.

---

## Technologies Used

- **React**: For building the user interface.
- **JavaScript**: Logic for typing tests and metrics calculation.
- **CSS**: Styling and layout.

---

## Installation

Follow these steps to set up and run the app locally:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/typing_tester.git
   cd typing_tester

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/typing_tester.git
    cd typing_tester
    ```

2. **Install dependencies**:
    ```bash
    npm install
    ```

3. **Start the development server**:
    ```bash
    npm start
    ```

The app will run on `http://localhost:3000`.

---

## Usage

1. Open the app in your browser at `http://localhost:3000`.
2. Click the **Start** button to load a random paragraph.
3. Start typing in the input field.
4. Observe the app calculate and display your typing speed, mistakes, and accuracy.

---

## File Structure

```plaintext
typing_tester/
├── public/
│   └── index.html         # Root HTML file
├── src/
│   ├── components/
│   │   ├── SpeedTypingGame.js  # Main typing test component
│   │   └── TypingArea.js       # Displays the paragraph and user input
│   ├── App.js                 # Entry point for React app
│   ├── App.css                # Styling for the app
│   ├── index.js               # Main React render file
│   └── paragraphs.js          # Random paragraph data
├── package.json               # Dependencies and scripts
└── README.md                  # Project documentation
