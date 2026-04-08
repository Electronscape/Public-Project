# Project Journal

A public development journal documenting projects, experiments, tools, and technical work as they are developed.

This repository contains a mix of work across several areas, including:

- electronics
- firmware
- games
- demos
- tools
- engine experiments
- other technical projects and prototypes

This is not intended to be a single polished product or a tightly packaged release repository.

Instead, it is structured as an open journal or workshop space: a place where people can browse through entries, explore the code, follow the development process, and reuse any parts that may be useful to them.

---

## Public Code

Everything in this repository is public.

If you find code, ideas, systems, structures, techniques, or tools here that are useful, you are welcome to use them in your own work. You may adapt, extend, remix, or build on anything in this repository.

There are no formal restrictions attached.

If something here proves helpful, a small credit or nod in my direction would be appreciated, but it is not required.

The purpose of this repository is to keep the work open, accessible, and available to others.

---

## About This Repository

This repository is organised more like a journal than a traditional project page.

It may include:

- early experiments
- rough prototypes
- working demos
- editor tools
- firmware tests
- graphics experiments
- game systems
- technical ideas in development
- projects that are useful or interesting enough to document and keep

Some entries will be small and focused.  
Others will be more complete.  
Some will be refined, while others may remain experimental.

That is intentional.

The aim of this repository is to document the development process as much as the finished result.

---

# Journal Entries

---

## Entry 001 — RC3D Raycasting Demo  
### RC3D Editor + Game Player Engine

The first entry in this journal is the current **RC3D raycasting demo**, built around two connected components:

- **RC3D Editor**
- **Game Player Engine**

This project is focused not only on rendering a raycasted scene, but on building both the **tooling** and the **runtime** together, so the work develops as a practical and usable workflow rather than as an isolated rendering test.

### RC3D Editor

The **RC3D Editor** is the content creation and map editing side of the project.

Its purpose is to make building and adjusting levels more efficient and more practical than relying entirely on hardcoded data.

The editor is intended to support:

- creating and shaping map geometry
- editing vertices and wall structures
- building level layouts visually
- adjusting sectors and spatial flow
- testing map ideas quickly
- improving iteration speed during development

In short, this is the part of the project used to construct and refine the world.

### Game Player Engine

The **Game Player Engine** is the runtime side of the project.

This is the component that takes map data produced for the demo and puts it into motion by rendering the world, handling movement and interaction, and providing a playable environment for testing.

It is responsible for:

- loading map and level data
- rendering the raycasted scene
- running player movement and interaction
- testing the world in real time
- validating that editor-created content works in practice

This is the part that turns the project from an editing tool into a functioning engine demo.

### Why this entry matters

What makes this entry important is that it represents more than a standalone rendering experiment.

It is the beginning of a proper workflow in which the two sides of the project support one another:

- the **editor** builds the world
- the **engine** runs the world

That makes the project more useful as a foundation for further work, testing, and future expansion.

### Current direction

This demo sits within a broader interest in practical real-time rendering systems, engine development, and usable technical tools.

The current focus is on building something that is:

- workable
- understandable
- extendable
- useful as both a demo and a foundation for future development

Like most work in this repository, it will continue to evolve as features are added, ideas are refined, and the overall system becomes more capable.

### Video

A video of the current RC3D raycasting demo can be found here:

**YouTube:** [RC3D Raycasting Demo](https://youtu.be/y9OKEO7IwvA)

---

## More Entries to Follow

This is only the beginning.

Future entries in this journal may include work in areas such as:

- electronics projects
- embedded systems
- firmware development
- game engine experiments
- graphics tools
- demoscene-style demos
- rendering tests
- smaller technical side projects

If you are here to browse, learn, reuse ideas, or explore specific parts of the code, that is exactly what this repository is intended for.

---

## Final Note

This repository is open by design.

Feel free to explore it, study it, reuse parts of it, and build on anything that proves useful.

And if something here helps you, a small credit would be appreciated.

That is all.
