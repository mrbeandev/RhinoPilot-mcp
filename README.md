![ICON-300x300](https://github.com/user-attachments/assets/c8be34db-d13a-44f5-970c-0250c75a7a3d)

# RhinoPilot MCP - AI-Driven 3D Modeling for Rhino

RhinoPilot MCP (Model Context Protocol) is a cutting-edge server extension for Rhino that revolutionizes how designers interact with 3D modeling. This professional-grade solution provides a sophisticated bridge between artificial intelligence systems and Rhino's powerful geometric modeling capabilities, enabling an unprecedented paradigm in creative design workflows.

## Key Features

### Advanced AI-Driven Geometry Creation
Transform natural language instructions into precise, production-ready 3D models through the Model Context Protocol interface. Create everything from simple primitives to complex parametric structures with intuitive commands and intelligent handling of validation and error checking. The system expertly interprets spatial relationships, dimensions, geometric constraints, and design intent to produce accurate models based on your descriptions.

### Enterprise-Grade Architecture
Built on a secure, high-performance client-server architecture, RhinoPilot MCP offers industrial-strength encrypted communication between AI systems and Rhino. With comprehensive error handling, parameter validation, and robust exception management, it ensures reliable operation even with the most complex design requests. The plugin maintains session consistency, handles concurrent modeling operations, and provides detailed feedback for every step of the modeling process.

### Comprehensive Geometry Toolkit
The plugin supports an extensive range of geometric operations:
- Basic primitives (points, lines, curves, surfaces) with parametric control
- Advanced solids and boundary representations (boxes, spheres, cylinders, cones)
- NURBS surfaces with precise control point manipulation
- Sophisticated mesh operations with customizable resolution
- Boolean operations and transformations with history support
- Intelligent layer management and organizational structure
- Metadata tagging and semantic object relationships

### Specialized Creative Modeling Tools
The plugin includes professional-grade tools for generating:
- Architectural elements (buildings, urban environments, pavilions, interior spaces)
- Organic forms (coral reefs, tree structures, natural landscapes, biological models)
- Mathematical art (Fibonacci patterns, Voronoi structures, parametric surfaces, fractals)
- Abstract sculptures and artistic installations with customizable parameters
- Parametric design systems with variable inputs and constraints
- Terrain modeling and topographic surface generation

### Developer-Focused API Interface
Featuring a comprehensively documented API with clear parameter schemas and examples, RhinoPilot MCP is designed for seamless integration with AI assistants, custom applications, or your own scripts for automated modeling workflows. The server exposes a standardized API following the Model Context Protocol specification, making it compatible with a growing ecosystem of AI-driven design tools and future-proofing your workflow investment.

## Practical Applications

- Conceptual Design: Rapidly develop and iterate on design concepts through natural language descriptions, accelerating the ideation phase
- Professional Prototyping: Transform concepts into architectural and product design prototypes with precision and speed
- Advanced Generative Design: Explore algorithmic and AI-driven design spaces with precise geometric output and constraint-based optimization
- Interactive Education: Teach parametric modeling concepts through an intuitive, AI-assisted interface that bridges theory and practice
- Design Research: Provide a robust platform for exploring cutting-edge AI-driven design methodologies and workflows
- Client Visualization: Quickly generate high-quality 3D visualizations for presentations and client communication
- Custom Tool Development: Create specialized modeling tools for specific design challenges and workflows
- Workflow Automation: Streamline repetitive modeling tasks through AI-driven process automation

RhinoPilot MCP bridges the gap between conceptual thinking and technical execution, allowing designers to focus on creative ideas while the system handles the technical implementation. Whether you're an architect visualizing complex structures, an artist exploring generative design, a product designer optimizing forms, or a researcher investigating AI-driven modeling, RhinoPilot MCP provides the professional tools to transform your ideas into precise 3D geometry.

## System Requirements

- Rhino 7 or later
- Windows 10/11 (64-bit)
- 8GB RAM minimum (16GB recommended for complex models)
- Node.js 18.0.0 or later (for the MCP server)
- 500MB free disk space
- Internet connection for AI service integration (optional)

## Installation Guide

1. Rhino Plugin Installation:
   - Open Rhino and type `_PackageManager` in the command line
   - Search for "RhinoPilotHelper-Plugin" and click Install
   - Alternatively, download the plugin from Food4Rhino and install manually

2. MCP Server Installation (choose one method):
   - Option A - MCP Server Config:
    ```json
    {
        "mcpServers": {
            "RhinoPilot": {
                "command": "npx",
                "args": [
                    "@mrbeandev/rhinopilot-mcp"
                ]
            }
        }
    }
    ```

   - Option B - Direct Execution:
     ```
     npx @mrbeandev/rhinopilot-mcp
     ```

3. Plugin Configuration:
   - Launch Rhino and type `RhinoPilot` to open the configuration panel
   - Connect to your local MCP server (default: localhost:3030)
   - Optional: Configure advanced settings and preferences

4. Connect AI Assistant or Custom Application:
   - Point your AI assistant or application to the MCP server endpoint
   - Begin creating models through natural language instructions

## Documentation & Support

For technical support, feature requests, or licensing inquiries:
mrbeandev@gmail.com

## Package Information

- Plugin Name: `RhinoPilotHelper-Plugin` (for Rhino Package Manager)
- NPM Package: `@mrbeandev/rhinopilot-mcp`
- Food4Rhino - [rhinopilot-helper](https://www.food4rhino.com/en/app/rhinopilot-helper)
- Version: 2.1.7
