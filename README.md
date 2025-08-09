KOCHU MEENUM, PERIYA TROUBLUM
Basic Details
Team Name: SPARKLES

Team Members

Member 1: SAM PETER - NSSCE

Member 2: RIYA ROSE ROY - NSSCE

Project Description
An interactive AI-powered virtual pet fish that lives in a digital tank on your desktop. It reacts to your presence using computer vision, expressing complex emotions like hunger, fear, and even sass. It can be fed, scared, taunted, and commanded to perform a spectacular dance routine.

The Problem (that doesn't exist)
The profound existential loneliness of the common pet fish is a silent crisis plaguing households everywhere. They swim in endless, monotonous circles, their tiny fish brains devoid of purpose or personality. Furthermore, potential fish owners are burdened by the tedious, soul-crushing tasks of cleaning tanks and remembering to feed their aquatic wards.

The Solution (that nobody asked for)
We present a revolutionary digital habitat that liberates fish from their aquatic prisons and owners from their responsibilities. Our AI fish isn't just surviving; it's living. It experiences hunger, fear, joy (when dancing), and even develops a sassy attitude, taunting its human overlord via text-to-speech. It's all the personality of a pet with none of the wet, smelly cleanup.

Technical Details
Technologies/Components Used
For Software:

Languages used: Python

Frameworks used: Pygame

Libraries used: OpenCV-Python, NumPy, MediaPipe, gTTS (Google Text-to-Speech)

Tools used: Visual Studio Code, Command Prompt/Terminal

For Hardware:

List main components: A standard PC (Windows/macOS/Linux), an integrated or external webcam.

List specifications: A dual-core processor and 4GB RAM should be sufficient.

List tools required: Just your hands for the hand-tracking interaction!

Implementation
For Software:
Installation

Bash

pip install pygame opencv-python numpy mediapipe gTTS
Run

Bash

python fish_tank_simulator.py


Project Documentation
For Software:
<img  src="https://github.com/user-attachments/assets/d45131a9-3df2-4b4a-8f32-824d9005dc80" />



The default state of the AI Fish Tank, with our hero, Kochu Meen, peacefully wandering near some plants.

The user interacting with the fish using hand tracking. The hook appears, and the fish gets scared, triggering a panic spin against the wall.

Party time! The fish performing its spectacular vertical dance routine after the 'd' key is pressed.




Project Demo
Video<https://drive.google.com/file/d/1Kae0qyZiw8ACh5J8Y622nOfOoKAahY97/view?usp=drivesdk>


This video demonstrates the core features: the fish's autonomous wandering, the feeding mechanism, the flee response from the user's hand, the TTS-based taunts, and the key-triggered vertical dance sequence.

Team Contributions
SAM PETER: Core AI behavior programming (seeking, fleeing, wandering), state machine implementation (dancing, spinning), and integrating the MediaPipe hand tracking module.

RIYA ROSE ROY: Game loop setup with Pygame, asset creation and integration (graphics, sound), UI/UX design (hunger bar, text bubbles), and implementing the gTTS text-to-speech feature.

Made with ❤️ at TinkerHub Useless Projects
