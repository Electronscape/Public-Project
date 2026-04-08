# Project Journal

A public development journal of things I build, experiment with, break, fix, and occasionally drag into existence properly.

This repository is a mix of projects and ideas, including:

- electronics
- firmware
- games
- demos
- tools
- engine experiments
- whatever else ends up on the bench

It is not meant to be one single polished product.

Instead, this repo is more like an open journal or workshop space — a place where people can browse through entries, look at the code, pick out the bits they like, and use whatever is useful to them.

---

## Public Code — Use What You Want

Everything in this repository is public.

If you find code, ideas, systems, snippets, structures, techniques, or tools here that are useful to you, feel free to use them.  
Take what you want, adapt it, remix it, learn from it, improve it, or drag parts of it into your own projects.

There are no strings attached.

The only thing I’d *maybe* ask is a small nod in my direction if something here helped you out — but even that is not a requirement.

The point of this repo is openness.  
Code should be useful, accessible, and easy to dig through.

---

## What This Repository Is

This repo is organised more like a journal than a traditional release page.

That means it may contain:

- early experiments
- rough prototypes
- working demos
- editor tools
- firmware tests
- graphics experiments
- game systems
- half-mad technical ideas that turned out better than expected
- and sometimes things that are simply interesting enough to keep

Some entries will be small.  
Some will be more complete.  
Some will be clean.  
Some will be a bit rough around the edges.

That is intentional.

This repository is here to document the process as much as the result.

---

# Journal Entries

---

## Entry 001 — RC3D Raycasting Demo  
### RC3D Editor + Game Player Engine

The first entry in this journal is the current **RC3D raycasting demo**, built around two connected parts:

- **RC3D Editor**
- **Game Player Engine**

This project is about more than just throwing a raycaster on screen and calling it done.  
The aim is to build both the **tool side** and the **runtime side** together, so the project has an actual workflow behind it.

### RC3D Editor

The **RC3D Editor** is the map-building and editing side of the project.

It exists to make building and adjusting levels far easier than hardcoding every little thing by hand like some sleep-deprived cave goblin with a keyboard problem.

The editor is there to help with:

- creating and shaping map geometry
- editing vertices and wall structures
- building level layouts visually
- adjusting sectors and room flow
- testing ideas quickly
- making iteration faster and less painful

In other words, this is the part that helps construct the world.

### Game Player Engine

The **Game Player Engine** is the runtime side of the project.

This is the part that takes the map data and actually does something useful with it: rendering the world, handling movement, and acting as the playable side of the demo.

It is the part responsible for:

- loading map / level data
- rendering the raycasted scene
- running player movement and interaction
- testing the world in real time
- proving that the editor output works in practice, not just in theory

This is what turns the project from “a map editor” into an actual engine demo.

### Why this entry matters

What makes this entry important to me is that it is not just a rendering test.  
It is the start of a proper workflow.

The editor and the player engine support each other:

- the **editor** builds the world
- the **engine** runs the world

That makes the project far more useful than a one-off experiment.  
It becomes something that can grow, be tested properly, and be pushed further over time.

### Current direction

This demo is part of a larger interest in practical, structured real-time rendering tools and game systems.

The focus right now is on building something that is:

- workable
- understandable
- extendable
- fun to experiment with
- useful as both a demo and a foundation

Like most things in this repo, it will likely continue to evolve as ideas improve, features get added, and bad decisions are identified and publicly shamed.

### Video

A video of the current RC3D raycasting demo can be found here:

**YouTube:** [https://youtu.be/y9OKEO7IwvA]

---

## More entries later

This is only the start.

Future entries in this journal may include more work in areas like:

- electronics projects
- embedded systems
- firmware development
- game engine experiments
- graphics tools
- demoscene-style demos
- rendering tests
- odd little technical side-projects

So if you are here to browse, borrow, learn, or just poke around for interesting parts, that is exactly what this repo is for.

---

## Final note

This repository is open by design.

Look through it.  
Pick out what is useful.  
Take inspiration.  
Take code.  
Build something better with it.

And if something here ends up helping you out, a nod would be appreciated.

That’s all.
