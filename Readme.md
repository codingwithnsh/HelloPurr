# Hello Purr

**Hello Purr** is a beginner-friendly mobile app project created using **MIT App Inventor**. It introduces the basics of app development in an engaging way by combining images, sounds, and simple interactions.

## Features
- **Interactive Image**: Tap on the image of a cat to trigger a response.
- **Sound Effect**: Plays a meowing sound whenever the image is tapped.
- **Beginner-Friendly**: Designed as an easy-to-follow project for first-time app developers.

## How It Works
1. **ImageButton**: A clickable image component displays a picture of a cat.
2. **Sound Component**: An audio file of a cat's meow is preloaded into the app.
3. **Block-Based Programming**: Simple drag-and-drop logic connects the tap event to the sound playback.

## Requirements
- MIT App Inventor platform ([https://appinventor.mit.edu](https://appinventor.mit.edu)).
- A mobile device or emulator to test the app.
- An audio file of a cat's meow (e.g., `meow.mp3`).

## Setup Instructions
1. Open MIT App Inventor and create a new project named `HelloPurr`.
2. Add the following components to the Designer:
   - **Image**: Set the source to an image of a cat.
   - **Button**: Link the image to a button (optional, or use an ImageButton).
   - **Sound**: Upload the `meow.mp3` file in the Media section.
3. Switch to the Blocks editor:
   - Create an event handler to trigger the sound when the image or button is tapped.
   - Use the `play` block from the Sound component.
4. Test your app on a connected mobile device or emulator.

## Example Code Blocks
```plaintext
When ImageButton1.Click
    Call Sound1.Play
