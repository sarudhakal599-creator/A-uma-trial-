# UMA AI Chat Interface

## Project Description

This repository contains a React-based chat interface designed to interact with the Gemini API. It features a modern, mobile-first dark UI, real-time message display, image upload capabilities, and a sleek loading animation. The interface is built with React and styled using TailwindCSS, providing a responsive and visually appealing user experience.

## Features

- **Gemini API Integration**: Seamlessly communicates with the Gemini-2.5-Flash model for AI responses.
- **Mobile-First Dark UI**: Optimized for mobile devices with a dark theme for reduced eye strain.
- **Image Upload**: Users can upload images to be sent as part of their prompts to the AI.
- **Real-time Chat Display**: Messages are displayed in real-time as they are sent and received.
- **Loading Indicator**: A subtle loading animation indicates when the AI is processing a response.
- **Clear Chat Functionality**: Easily clear all messages to start a new conversation.

## Technologies Used

- **React**: A JavaScript library for building user interfaces.
- **TailwindCSS**: A utility-first CSS framework for rapid UI development.
- **Gemini API**: Google's multimodal AI API for generating responses.
- **Framer Motion**: (Likely used for animations, based on `AnimatePresence` and `motion.div` in the code).

## Setup and Installation

To get this project up and running on your local machine, follow these steps:

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/sarudhakal599-creator/A-uma-trial-
    cd A-uma-trial-
    ```

2.  **Install dependencies**:
    ```bash
    npm install
    # or yarn install
    ```

3.  **Configure Gemini API Key**:
    Create a `.env` file in the root of the project and add your Gemini API key:
    ```
    VITE_GEMINI_API_KEY=YOUR_GEMINI_API_KEY
    ```
    Replace `YOUR_GEMINI_API_KEY` with your actual API key obtained from the Google AI Studio.

4.  **Run the application**:
    ```bash
    npm run dev
    # or yarn dev
    ```
    The application should now be running on `http://localhost:5173` (or another port as indicated in your terminal).

## Usage

- Type your message in the input field at the bottom of the screen.
- Click the paper airplane icon or press Enter to send your message.
- To include an image with your message, click the image icon and select an image file.
- Click the 'Clear Chat' button in the top bar to clear all messages.

## Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues for any bugs or feature requests.

## License

This project is open-sourced under the MIT License. See the `LICENSE` file for more details. (Note: A `LICENSE` file should be added if not present.)
