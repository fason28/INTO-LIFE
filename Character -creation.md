# Character Creation System

## Overview
When a new player creates an account in "Into Life", the game will generate a 3D character that looks like the real player.

## Process (Planned)
1. Player creates account (username, email, password, etc.).
2. Player is asked to take a selfie / photo of their face using the device's camera.
3. The game automatically processes the photo and creates a 3D character head/face that matches the player's appearance as closely as possible.
4. Player can then customize other parts (hairstyle, clothing, body type, skin tone, etc.) if they want, but the face is based on the real photo.

## Notes for First Prototype
- In the very first tiny prototype (graduation scene), we will use a simple placeholder character model.
- The real photo-to-3D face system will be implemented much later.
- This feature is important for immersion — players should feel "this is me living my life".

## Technical Ideas (Later)
- Use device camera access (Godot supports this on mobile).
- Simple face generation or morphing system.
- Store the generated character data with the player's save file.
- Make sure it works on both PC and mobile.

## Goals
- Make the player feel connected to their character from the very beginning.
- Keep customization simple and optional after the automatic face generation.
