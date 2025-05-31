<BS># 🚀 Game/Physics Engine in C++

A custom game and physics engine built from scratch using C++ on Linux. This project aims to explore low-level system programming, real-time physics simulation, and game engine architecture.

The objective is to learn why current engines make the choices they make by encountering the same type of problems that motivated their choices.

---

## Technical Goals

- Modular, extensible engine architecture
- Real-time 2D/3D physics simulation
- Custom math and utility libraries
- Rendering with OpenGL or Vulkan
- Scene management and entity-component system (ECS)
- Cross-platform support (initially Linux)

---

## Roadmap

### Phase 1: Core Systems

- [ ] Project structure & CMake setup
- [ ] Basic math library (Vec2, Vec3, Mat4, etc.)
- [ ] Logging and debug utilities
- [ ] Time & deltaTime system

### Phase 2: Physics Engine

- [ ] Collision detection (AABB, Circle, OBB, Ray)
- [ ] Physics solver (impulse resolution, constraints)
- [ ] Broadphase (e.g., spatial hashing or BVH)
- [ ] Rigid body dynamics (2D/3D)

### Phase 3: Engine Architecture

- [ ] ECS (Entity Component System)
- [ ] Event system
- [ ] Scene management
- [ ] Resource manager (textures, meshes, sounds)

### Phase 4: Rendering

- [ ] OpenGL/Vulkan rendering backend
- [ ] Shader system
- [ ] 2D renderer
- [ ] 3D renderer
- [ ] Lighting and shadows (basic)

### Phase 5: Game Framework

- [ ] Input system (keyboard, mouse, controller)
- [ ] Game loop
- [ ] Scripting support (Lua or custom DSL)
- [ ] Audio engine (OpenAL, SDL_mixer, etc.)

### Phase 6: Tools and Extensibility

- [ ] GUI editor (Dear ImGui integration)
- [ ] Serialization (JSON, YAML)
- [ ] Level editor
- [ ] Plugin system
