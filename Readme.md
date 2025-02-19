
# Replica - Create Your Clone

Welcome to the "Replica - Create Your Clone" project, built for the Nosu Superflex Hackathon. This project allows you to create a personalized AI clone, utilizing various APIs to provide a dynamic experience.

## Setup Instructions

### 1. Clone the Repository
Clone the repository to your local machine by running:

```bash
git clone https://github.com/shresthasingh1501/replica.git
```

### 2. Install Dependencies
Navigate to the project directory and install the required dependencies:

```bash
cd replica
npm install
```

### 3. Create `.env` File
You need to create a `.env` file in the root directory to store API keys for the project. In the `.env` file, include the following variables:

```bash
REACT_APP_GROQ_API_KEY=<your-groq-api-key>
REACT_APP_ELEVENLABS_API_KEY=<your-elevenlabs-api-key>
REACT_APP_TOGETHERAI_API_KEY=<your-togetherai-api-key>
```

### 4. Start the Project
Once everything is set up, you can start the project by running:

```bash
npm start
```

This will start the development server, and you can access the application in your browser at `http://localhost:3000`.

## Environment Variables

The following environment variables must be set in your `.env` file:

- `REACT_APP_GROQ_API_KEY`: Your GROQ API key.
- `REACT_APP_ELEVENLABS_API_KEY`: Your ElevenLabs API key.
- `REACT_APP_TOGETHERAI_API_KEY`: Your TogetherAI API key.

Make sure to replace `<your-groq-api-key>`, `<your-elevenlabs-api-key>`, and `<your-togetherai-api-key>` with actual values from the respective services.

## License

This project is built for the Nosu Superflex Hackathon and is open for use under the MIT License.
