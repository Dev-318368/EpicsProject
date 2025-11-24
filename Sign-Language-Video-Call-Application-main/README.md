What is this Project?
Think of this as "Skype or Zoom with a built-in translator." It is a website where two people can video chat.

If you use Sign Language, the camera watches your hands and writes down what you are signing.

If you Speak, the computer hears you and shows pictures of sign language gestures to the other person.

Key Features (What can it do?)
Video Chat: You can see and hear the other person in real-time.

Smart Camera: It uses Artificial Intelligence (AI) to recognize your hand movements.

Voice Translator: If you speak, it converts your words into sign language images.

Private Rooms: You create a specific "room" with a secret code so only your friend can join.

What You Need (Prerequisites)
Before you start, you need a computer with:

Python: A programming language installed on your computer.

A Browser: Chrome, Firefox, or Edge.

Hardware: A working webcam and microphone.

How to Set It Up (Installation)
Get the files: Download the project folder to your computer.

Create a workspace: Run a command to create a "virtual environment." This is like a clean, separate box for this project so it doesn't mess up other things on your computer.

Install tools: Run the command pip install -r requirements.txt. This tells Python to go download all the helper tools (like the AI brain) needed to run the app.

How to Run It
Start the Engine: Open your command prompt and type python app.py. This turns on the server (the brain of the app).

Open the App: Go to your web browser and type http://localhost:5000. The website will appear.

How to Use It (Step-by-Step)
Start a Call: Click "Create Room." The app will give you a random Room ID (like a password).

Invite a Friend: Send that Room ID to your friend.

Friend Joins: Your friend opens the site, types in that Room ID, and clicks "Join Room."

Chat:
Toggle your camera and mic on.

Show your hands to the camera to have the AI read your signs.

Speak into the mic to see your words turn into sign language images.

How It Works (The Magic Behind the Scenes)
The Brain (Machine Learning): The app uses a tool called MediaPipe. Imagine an invisible skeleton that draws lines on your hands to track exactly where your fingers are moving.

The Connection (WebRTC): This technology connects your computer directly to your friend's computer so the video is fast.

The Messenger (WebSockets): This sends messages back and forth instantly, like "User joined the room" or "He just signed the letter A."