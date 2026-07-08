# Architecture

The project is structured around a modular rendering engine and a higher-level widget layer.

## Proposed module layout

- engine/ - core engine services and lifecycle
- renderer/ - GPU rendering logic, buffers, textures, and draw calls
- shaders/ - HLSL shader sources
- capture/ - desktop capture pipeline
- materials/ - material definitions for glass, metal, plastic, and future surfaces
- widgets/ - reusable widget components
- animation/ - timing, easing, and motion systems
- docs/ - design notes and contributor guides
- tests/ - automated tests

## Current starter layout

The repository currently uses a simple layout:

- src/ - main executable entry point
- docs/ - planning and collaboration documents

This gives the project a solid base for future expansion without locking in too much structure too early.
