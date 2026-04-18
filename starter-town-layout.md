# Starter Town Layout - First Prototype

## Overview
The very first explorable area after the black "Welcome Into Life......" screen.  
Kept intentionally small and simple for the initial prototype.

## General Feel
- Quiet, realistic small town/village area just outside the school.
- Not overwhelming — enough space to walk and explore, but not a huge open world yet.
- Calm atmosphere with slight uncertainty and excitement.

## Basic Layout (Simple Version)

- **Starting Position**: Player spawns on a small road just past the school gate.
- **School Gate**: Behind the player (can turn around and see the school building).
- **Main Path**: A straight or slightly curved road leading forward.

### Key Landmarks (Visible from Start)
1. **School Building** (behind player) - Can look up at it in first-person.
2. **Notice Board** - On the left side of the road (first interaction point).
3. **Small Hostel Building** - A simple building further down the road.
4. **Internet Café** - Another small building, maybe with a sign.
5. **Bus Stop / Bench** - Simple decorative element.
6. **Trees and Basic Greenery** - To make the area feel alive.

## Scale
- The entire starter area should be small enough that the player can walk from one end to the other in about 1-2 minutes.
- Use low detail (basic shapes) for performance, especially on mobile.

## Navigation
- Clear but natural paths.
- No mini-map in first prototype.
- Player must explore by walking and looking around.

## Future Expansion Plans
- This small area will later connect to a larger starter town.
- More buildings: university admin office, job centers, shops, etc.
- Eventually support multiple players walking in the same space.

## Development Notes
- Use simple MeshInstance3D + basic materials for buildings.
- Ground can be a large PlaneMesh with texture later.
- Keep lighting simple (DirectionalLight3D + ambient).
- Test movement and first-person camera here first.

## Goal
Player should feel free to wander, discover the advice on the notice board, and decide where to go next — without any hand-holding.

Last updated: April 2026