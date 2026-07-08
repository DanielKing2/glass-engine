# GlassEngine

GlassEngine is an open-source, native Windows rendering engine for building physically inspired glass interfaces, desktop widgets, and immersive UI experiences.

This repository is an early base idea, not a finished product. The goal is to start small, learn as we go, and invite other people to improve the architecture, rendering, shaders, UI ideas, documentation, and first widgets.

This project is meant to be a collaborative effort. If you know C++, Windows graphics, Direct3D, UI/UX, shaders, documentation, or testing, your help would be valuable.

This repository is the starting point for a long-term project that aims to combine:

- GPU-accelerated rendering
- Direct3D 11 and shader-driven effects
- Desktop capture and compositing
- Glass-like materials such as refraction, reflection, highlights, and blur
- A modular widget framework for future applications

## Why this project exists

The goal is not to make a simple "glass app" that only looks pretty. The goal is to build a reusable engine that can power high-quality, performant, native Windows interfaces.

## Current status

This repository currently contains the initial project skeleton and a simple buildable starter executable. The next milestone is to turn this into a transparent window and then a basic rendered rectangle.

## How people can help

- Improve the architecture and folder layout
- Help build the first transparent window
- Suggest better glass rendering ideas
- Add shaders, effects, or animation concepts
- Improve documentation and onboarding for new contributors
- Help turn this into a cleaner open-source project

## Project structure

- src/ - application entry point and initial engine skeleton
- docs/ - planning, outreach, and contributor materials
- tests/ - future automated tests

## Quick start

### Windows with Visual Studio 2022 and CMake

1. Install Visual Studio 2022 with C++ tools
2. Install CMake
3. Open the repository folder in VS Code
4. Configure the project with CMake
5. Build and run the executable

## Vision

See [VISION.md](VISION.md) for the long-term direction.

## Roadmap

See [ROADMAP.md](ROADMAP.md) for milestones.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for contribution guidelines.
