TERRASCAN | SPATIAL ELEMENT SIMULATION ANALYSIS

TERRASCAN is a high-fidelity, web-based civil engineering and geological simulation suite. It bridges the gap between raw surveying data and structural BIM (Building Information Modeling) design by providing a "Terra-Mechanical" environment for real-time evaluation, volumetric geology analysis, and structural stress testing.

🛠 Core Capabilities

1. Multi-Workspace Navigation

The application is categorized into three distinct operational environments:

Survey Workspace: Focused on topographic evaluation and sub-surface strata inspection. Features a LiDAR-style wireframe terrain.

BIM Design Workspace: Provides a professional hierarchy for managing structural elements (IFC/OBJ), inspecting metadata, and spatial organization.

Analysis Workspace: A dedicated environment for Finite Element Analysis (FEA) solvers, stability calculations, and safety factor reporting.

2. Volumetric Geology Engine

Unlike standard surface-mesh tools, TERRASCAN simulates sub-surface strata including:

Topsoil, Expansive Clay, and Igneous Bedrock layers.

Dynamic Water Table adjustments.

Real-time Section Cutting (Spatial Slicing) to view foundation-to-soil relationships.

3. BIM & Data Ingestion

IFC Export: Generates formal IFC 2x3 Physical Files (STEP format) for interoperability with external CAD software.

Asset Ingestion: Supports drag-and-drop or manual import for .obj and .ifc files.

Inspector: Deep-dive into GUIDs, material strengths, and load calculations via a raycasting selection engine.

🎮 Interface & Controls

Navigation

Left Click + Drag: Orbit scene.

Right Click + Drag / Shift + Click: Pan scene.

Scroll: Zoom in/out.

Double-Click (Hierarchy): Focus camera on specific structural entity.

Hotkeys

[T]: Switch to Survey Mode.

[B]: Switch to BIM Design Mode.

[G]: Switch to Volumetric Geology Mode.

[Space]: Reset to Isometric Home View.

🚀 Technical Stack

Rendering: Three.js (WebGL)

Styling: Tailwind CSS

Icons: Lucide-React

Fonts: Inter & JetBrains Mono

📂 Installation

TERRASCAN is a single-file application.

Download terraforge_pro.html.

Open in any modern browser (Chrome/Edge recommended for performance).

No server-side installation required; all logic runs in the client-side kernel.

Developed for advanced spatial element simulation and structural integrity evaluation.
