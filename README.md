# Cluster Notes

Live Demo: [https://rencheng0525.github.io/ClusterNotes/](https://rencheng0525.github.io/ClusterNotes/)

Generated by Claude with prompts only, no manual code editing. Took 1.5 hours.

## Overview
Cluster Notes is a web-based interactive sticky note system that allows users to create, move, group, and manage notes in an intuitive visual interface. The application automatically detects clusters of nearby notes and organizes them within interactive bubble outlines.

## Features

### Visual Components
- **Sticky Notes**: Customizable notes with different colors and editable text.
- **Automatic Clustering**: Notes placed close together automatically form a cluster with a surrounding bubble.
- **Cluster Titles**: Each cluster can be labeled with a custom title for better organization.
- **Selection Highlighting**: Selected notes are visually highlighted for easy identification.

### Interactive Features
- **Drag & Drop Notes**: Move sticky notes freely across the workspace.
- **Group Movement**: Drag a cluster’s bubble title to move all notes within that group.
- **Multi-Selection**: Use `Ctrl + Drag` to select multiple notes at once.
- **Color Customization**: Change the color of selected notes from a palette of 9 colors.
- **Note Deletion**: Delete selected notes with a confirmation prompt.

### Technical Highlights
- Built with **Vanilla JavaScript** for lightweight and efficient performance.
- Uses **LocalStorage** to persist notes and clusters across sessions.
- Implements **Bounding Box Collision Detection** to detect and manage clusters dynamically.
- Supports **smooth dragging interactions** for both individual notes and entire clusters.

### Use Cases
- Brainstorming and idea organization
- Task and project management
- Collaborative planning in team settings
- Interactive sticky note visualization

### Implementation Details
- **Dynamic Clustering**: Uses proximity-based detection to create clusters.
- **LocalStorage Persistence**: Saves and loads notes automatically between sessions.
- **Event-Driven UI**: Click, drag, and keyboard shortcuts enhance user interaction.
- **Selection Mechanism**: Implements a selection box for multi-note selection.
- **Customizable Note Colors**: Allows users to personalize notes for better categorization.

## License
MIT License

---

*Note: Cluster Notes demonstrates how interactive note-taking can be enhanced with visual organization and clustering mechanics, making brainstorming and information structuring more intuitive and engaging.*
