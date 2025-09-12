🤖 AI Mentor in Unity — Powered by GPT-OSS
This project reimagines AI mentorship by combining Unity’s interactive interface with GPT-OSS’s open-weight intelligence—all running fully offline via Ollama. It simulates a robotics tutor that answers questions, explains concepts, and guides beginners through technical challenges without requiring cloud access or coding experience.
🎯 Features
- 🧠 Local AI chatbot using [GPT-OSS:20B] via Ollama
- 🎮 Unity UI with input field, animated “Thinking…” feedback, and clean response display
- 📶 Fully offline setup—ideal for classrooms, labs, or low-connectivity environments
- 🧪 Beginner-friendly responses tailored to robotics education
🛠️ Setup Instructions
1. Install Ollama
Download and install from https://ollama.com
2. Pull the GPT-OSS model
open the command run prompt and paste "ollama pull gpt-oss:20b" in it . This command tells Ollama (a tool that runs AI models locally) to download the GPT-OSS:20B model onto your computer.
- Start the Ollama server -write this in the command prompt  "ollama serve" and run it.
- When you run: ollama serve You're starting the Ollama server on your computer. This server acts like a local brain that listens for requests and responds using the GPT-OSS model you downloaded. Think of it like turning on a chatbot engine that Unity (or any app) can talk to.
- Open Unity Project
- Open the project in Unity Editor
- Press Play
- Type a question and click “Ask Mentor”
-
- 🧪 Testing Instructions
 ✅ Test Prompt Type your question into ask AI mentor

   🧪 To test the project locally:
1. Download and unzip the folder"robomentor_test.zip " from above.
2. Open the folder in **Visual Studio Code**
3. Install the **Live Server** extension (if not already installed)
4. Right-click `index.html` → choose **“Open with Live Server”**
5. The game will launch in your default browser


🧪 Example Prompts
- “How does a robot arm work?”
- “What is inverse kinematics?”
- “Give me a beginner challenge in robotics.”
🧠 Expected Response GPT-OSS will return a beginner-friendly explanation, such as: A robot arm is a mechanical device that mimics the movement of a human arm. It typically consists of joints, actuators, and sensors...
🧠 Model Weights & Training Data
- GPT-OSS model weights available via OpenAI’s GPT-OSS release
- Model used: gpt-oss:20b (no fine-tuning applied)
- Hosted locally using Ollama
Repository Info :
- License: Apache 2.0 (recommended)
- Model: GPT-OSS:20B via Ollama
- API Endpoint:  http://127.0.0.1:11434/api/chat Important: This endpoint only accepts POST requests. If you try to open it in a browser (which sends a GET request), you'll see a “Method Not Allowed” error. That’s expected.

