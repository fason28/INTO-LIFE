# Account Creation System - Into Life

## Overview
The moment a new player starts the game — this is their first impression and the beginning of their personal story.

## Step-by-Step Account Creation Flow

1. **Welcome Screen**
   - Game title "Into Life"
   - Buttons: "New Life" (Create Account) / "Continue Life" (Load existing)

2. **Basic Information**
   - Username (unique)
   - Email (for recovery)
   - Password / PIN (or use device login)
   - Date of Birth confirmation (player must be 16+ in real life for age rating)

3. **Character Creation (Most Important Step)**
   - Instruction: "Let's create you"
   - Player takes a **selfie** using their device's front camera
   - Game automatically generates a 3D character face that looks like the player
   - Player can then lightly customize:
     - Hairstyle
     - Skin tone adjustment
     - Clothing (simple school uniform at start)
     - Height / Body type (limited options)
   - Preview in real-time (rotating 3D model)

4. **Final Confirmation**
   - Show the character in a mirror or simple scene
   - Text: "This is you starting your life at 16"
   - Button: "Begin My Life" (starts the graduation ceremony)

## Technical Notes (For Later)
- Use Godot's Camera access for selfie (works on mobile + PC)
- Simple face generation system (morph targets or basic texture mapping at first)
- Save character data (face data + customization) with the account
- Privacy: Clearly explain that photo is only used locally to generate character (no upload unless player wants cloud save)

## Desired Feeling
- Exciting and personal
- Player should think: "This is really me in the game"
- Not too long or complicated (under 3-4 minutes total)

## Connection to First Prototype
- After account creation → directly load into the graduation ceremony hall (sitting in the chair)
- The generated character is used throughout the game

## Future Features
- Multiple outfits
- Aging system (character slowly looks older as years pass in game)
- Full body customization
- Option to change appearance later in game (barber, clothes shop)

Last updated: April 2026
