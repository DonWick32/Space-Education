# VR Space Education

## Project Overview

### Problem Statement
Introducing space education to kids serves as a gateway to fostering curiosity and scientific interest. To make learning about planets a thrilling adventure, this project utilizes virtual reality, interactive apps, and hands-on activities to provide immersive experiences for children. Additionally, testing a student’s understanding of the planets is a crucial aspect addressed through VR.

### Design

#### Application Building
The application is crafted using Unity, employing C# scripting and the XR Interaction Toolkit. All 3D assets and sounds used in the project are freely available on the internet.

#### Scene Construction
- First-person player movement + hands (oculus-compliant HMD controller)
- Rigid Body components on all surfaces for realistic physics
- Area lights for spaceship interior visibility
- Wormhole particle physics for teleportation visualization

#### Script Creation
The core logic of the game is encapsulated in various C# scripts handling different aspects:
- `PlanetController`: Manages interaction with planets using XR controllers.
- `QuizManager`: Handles the generation and assessment of quiz questions.
- `QuestionsAndAnswers`: Serves as a data structure for storing quiz questions and answers.
- `UIAndAudioController`: Manages UI updates and audio playback based on player interactions.
- `PlanetInstantiator`: Controls planet instantiation and triggers cutscene playback.
- `PlanetAnimate`: Applies animation effects to enhance planet visual appeal.
- `Planet`: Holds information about a planet, including its name, description, and associated audio.

### Tools Used
- Unity / C# 2022.3.12 (Latest Long-Term Support Version)
- Unity XR Interaction Toolkit and XR Device Simulator
- Unity Shader Graph and Timeline
- Blender
- Git (Version Control System)

## Instructions for Execution

1. Clone the repository or download the zip file.
2. Open the project in Unity.
3. Build and run the project on a compatible XR device (Oculus) or use the XR Device Simulator with the specified key bindings.

## Demo Video

[View Demo Video](https://drive.google.com/file/d/1n2rL6sfawbC5OIYs-ZjHUJ0650v1IZPZ/view)

## Novelty

1. **Immersive Education:** The project offers an immersive VR space learning environment for kids, utilizing XR controllers, Oculus-compliant HMD controllers, and realistic physics for an engaging educational experience.

2. **Interactive Planet Exploration:** Uniquely, the project allows hands-on interaction with planets using XR controllers and first-person movement, providing a distinctive way for children to explore and learn about celestial bodies.

3. **Gamified Learning Quizzes:** The inclusion of a Quiz Manager and interactive quizzes within the VR space adds a gamified dimension to education, allowing kids to test their knowledge about space and planets in an engaging manner.

4. **Multi-Sensory Experience:** Setting itself apart, the project incorporates freely available 3D assets and sounds, coupled with scripts for managing audio. This multi-sensory approach ensures a comprehensive and captivating educational experience for young users.

## GROUP - 13
**Team Members:**
- Aadarsh Anantha Ramakrishnan (106121001)
- Nitish N (106121087)
- S Selvanayagam (106121133)
