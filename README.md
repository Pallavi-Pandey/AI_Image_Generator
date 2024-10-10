
---

# AI Image Generator

The AI Image Generator is a web application that generates AI-based images based on text prompts. It utilizes a machine learning model to transform user descriptions into visual images in real time.

## Features

- **Text-to-Image Conversion**: Users can input custom text descriptions, and the application generates corresponding images.
- **Real-Time Rendering**: The generated images are displayed instantly within the application.
- **User-Friendly Interface**: Built with a responsive design for seamless interaction.

## Tech Stack

### Frontend:
- **React**: For building the user interface and handling interactions.
- **Tailwind CSS**: For styling the application.
  
### Backend:
- **Node.js**: As the runtime environment for the server.
- **Express.js**: To handle API requests and server-side logic.
- **AI Model**: The image generation functionality is powered by an AI model that processes text prompts.

### Database:
- **MongoDB**: Used for storing user information, image data, and history.

### Additional Libraries:
- **Axios**: For making API calls from the frontend to the backend.
- **Mongoose**: For connecting and interacting with the MongoDB database.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Pallavi-Pandey/AI_Image_Generator.git
   ```
   
2. Install the dependencies for both the client and server:
   ```bash
   # Install client dependencies
   cd client
   npm install
   
   # Install server dependencies
   cd ../server
   npm install
   ```

3. Start the application:
   - To run the frontend (React):
     ```bash
     cd client
     npm start
     ```
   - To run the backend (Node.js/Express):
     ```bash
     cd ../server
     npm run dev
     ```

4. The app will be available at `http://localhost:3000` (frontend) and `http://localhost:5000` (backend).

## Contributing

Feel free to fork the project and submit a pull request to contribute!

## License

This project is licensed under the [MIT License](LICENSE).

---
