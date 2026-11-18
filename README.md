# Wilds Engine

<img width="140" height="81" alt="image" src="https://github.com/user-attachments/assets/d50a30f5-5482-4e47-b42b-bfbeec69765f" />


**A hobby fork of Godot Engine** focused on Unity-like workflow, cross-fork unification, and practical game development features.

> **Status:** Personal / experimental project. Not under active development.  
> This is a long-term personal experiment. Expect incomplete features, breaking changes, and long periods of inactivity.

---

## Goals

Wilds aims to evolve Godot in several practical directions:

1. **Unity-inspired UI, Terminology & Structure**  
   Make the editor, project layout, and naming conventions feel more familiar to Unity users (e.g. Hierarchy, Inspector, Project window concepts, component-style thinking, scene/prefab workflow adjustments) without abandoning Godot’s core strengths.

2. **Unification Across Forks**  
   Act as a practical meeting point for useful features and improvements from Godot, Redot, Blazium, and other community forks. Prefer compatibility and selective merging over hard divergence.

3. **Unity Project & Asset Interoperability**  
   Explore partial (and eventually deeper) support for importing/using Unity projects, assets, and common workflows. Goal is practical interoperability rather than perfect 1:1 compatibility.

4. **Unreal-level 3D Graphics Ambition**  
   Push rendering quality, lighting, materials, and related systems toward higher-end visual fidelity closer to what Unreal Engine users expect, while remaining realistic about the scope of a hobby project.

5. **Built-in Steamworks SDK**  
   Integrate Steamworks support more tightly into the engine so Steam features (achievements, cloud, multiplayer, overlay, etc.) are easier to use out of the box.

6. **Built-in Source Control**  
   Provide first-class, integrated source control tooling inside the editor (beyond the existing basic VCS support) to make version control a natural part of the workflow.

---

## Philosophy

- **Hobby-first** — This is a personal project. Features will land when they land.
- **Pragmatic** — Prefer useful, usable improvements over purity or perfect architecture.
- **Respectful of upstream** — Stay close enough to Godot that useful changes can potentially flow both ways.
- **Honest about scope** — Many of the goals above are large. Progress will be incremental and uneven.

---

## Current Status

| Area                        | Status          | Notes |
|----------------------------|-----------------|-------|
| Base Godot fork            | Planned         | Starting point not yet chosen / frozen |
| Unity-like UI & naming     | Not started     | High priority concept |
| Fork feature unification   | Research        | Looking at Redot, Blazium, others |
| Unity project import       | Idea stage      | Very ambitious |
| High-end 3D rendering      | Idea stage      | Long-term goal |
| Steamworks integration     | Planned         | Desired for shipping games |
| Built-in source control    | Planned         | Quality-of-life focus |

This README will be updated if/when concrete work begins.

---

## Why “Wilds”?

A short, distinctive name that doesn’t collide with existing Godot forks. It also reflects the idea of exploring a less constrained, more “wild” direction from the main engine while remaining a fork rather than a complete rewrite.

---

## Relationship to Other Projects

- **Godot** — Upstream foundation. Wilds is a fork, not a competitor.
- **Redot / Blazium / other forks** — Potential sources of features and ideas. The long-term hope is selective unification rather than fragmentation.
- **Unity / Unreal** — Inspiration for workflow and visual targets, not direct competitors in the open-source space.

---

## Contributing / Feedback

This is currently a personal project with no active development schedule.  

If you are interested in the ideas above, feel free to open an issue for discussion. Pull requests are not expected at this stage.

---

## License

Wilds Engine will follow the same license as the Godot version it is based on (MIT).  
Any additional code written specifically for Wilds will also be released under MIT unless otherwise noted.

---

## Disclaimer

This project is experimental. It may never reach a usable state for real games. Use at your own risk. Do not rely on it for production work.

---

*Personal hobby project — last updated late 2026.*
