# Awesome Computational Design

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License](https://img.shields.io/github/license/CameronBrooks11/awesome-computational-design)](./LICENSE)
[![Stars](https://img.shields.io/github/stars/CameronBrooks11/awesome-computational-design)](https://github.com/CameronBrooks11/awesome-computational-design/stargazers)
[![PRs welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](#contributing)

A curated list of awesome open-source tools for computational engineering, data-driven design, scriptable tools, cyber-physical design, and computational science. This repository aims to provide engineers, designers, and researchers with the best resources to enhance their computational projects.

> _Viewable at https://cameronbrooks11.github.io/awesome-computational-design/_

## Table of Contents

- [Introduction](#introduction)
- [Tools](#tools)
  - [Parametric \& scripted CAD](#parametric--scripted-cad)
  - [Implicit \& volumetric modelling](#implicit--volumetric-modelling)
  - [Geometry \& meshing](#geometry--meshing)
  - [Simulation \& multiphysics](#simulation--multiphysics)
  - [Systems \& process modelling](#systems--process-modelling)
  - [Electronics \& PCB design](#electronics--pcb-design)
  - [Optimization](#optimization)
  - [Visualization \& mesh analysis](#visualization--mesh-analysis)
  - [Domain-specific](#domain-specific)
- [Contributing](#contributing)
- [Guidelines](#guidelines)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction

Welcome to the **Awesome Computational Design** repository! This list is intended for developers, engineers, and researchers who are looking for high-quality, open-source tools to aid in computational design and engineering projects. Whether you're working on CAD modeling, simulation, optimization, or data visualization, you'll find valuable resources here.

## Tools

Grouped by what you reach for them to do. Entries are alphabetical within each group.

### Parametric & scripted CAD

- [Antimony](https://github.com/mkeeter/antimony) — node-graph CAD built on a functional representation; "CAD from a parallel universe"
- [Build123d](https://github.com/gumyr/build123d) — Python CAD library over OCCT, with a builder and a direct algebra API
- [CadQuery](https://github.com/CadQuery/cadquery) — Python parametric CAD scripting framework based on OCCT
- [FreeCAD](https://github.com/FreeCAD/FreeCAD) — general-purpose parametric 3D modeller with a full Python API and workbenches per discipline
- [JSCAD](https://github.com/jscad/OpenJSCAD.org) — modular browser and CLI tools for parametric 2D/3D design in JavaScript (previously OpenJSCAD)
- [JupyterCAD](https://github.com/jupytercad/JupyterCAD) — JupyterLab extension for collaborative 3D geometry modelling
- [OpenSCAD](https://github.com/openscad/openscad) — the programmers' solid 3D CAD modeller; geometry described as code rather than drawn
- [SolidPython](https://github.com/SolidCode/SolidPython) — Python frontend for solid modelling that compiles to OpenSCAD
- [SolidPython (jeff-dh fork)](https://github.com/jeff-dh/SolidPython) — actively maintained fork of the above, with an expanded API
- [SolveSpace](https://github.com/solvespace/solvespace) — parametric 2D/3D CAD built on a geometric constraint solver

### Implicit & volumetric modelling

- [ImplicitCAD](https://github.com/Haskell-Things/ImplicitCAD) — math-inspired CAD in Haskell; CSG, bevels and shells, 2D/3D, G-code output
- [OpenVDB](https://github.com/AcademySoftwareFoundation/openvdb) — sparse volume data structure and tools, the industry standard for level sets
- [PicoGK](https://github.com/leap71/PicoGK) — compact geometry kernel for computational engineering, voxel/field based

### Geometry & meshing

- [Gmsh](https://gmsh.info/) — 3D finite element mesh generator with built-in pre- and post-processing ([source](https://gitlab.onelab.info/gmsh/gmsh))
- [Manifold](https://github.com/elalish/manifold) — geometry library for topologically robust mesh Booleans, used as a CSG backend by several tools here
- [OCCT](https://github.com/Open-Cascade-SAS/OCCT) — Open CASCADE Technology, the B-rep kernel underneath CadQuery, build123d and FreeCAD
- [scikit-geometry](https://github.com/scikit-geometry/scikit-geometry) — scientific Python geometric algorithms library, wrapping CGAL

### Simulation & multiphysics

- [Elmer FEM](https://github.com/ElmerCSC/elmerfem) — multiphysical FEM suite, strong on coupled and electromagnetic problems
- [FEniCSx](https://github.com/FEniCS/dolfinx) — solve PDEs by writing their variational form more or less as the maths reads
- [MOOSE Framework](https://github.com/idaholab/moose) — Multiphysics Object Oriented Simulation Environment, for tightly coupled multiphysics
- [openEMS](https://github.com/thliebig/openEMS-Project) — free electromagnetic field solver using the FDTD method
- [OpenFOAM](https://github.com/OpenFOAM/OpenFOAM-dev) — the CFD toolbox; finite volume solvers for essentially any continuum problem
- [SfePy](https://github.com/sfepy/sfepy) — simple finite elements in Python, for solving PDE systems

### Systems & process modelling

- [Cantera](https://github.com/Cantera/cantera) — chemical kinetics, thermodynamics and transport tool suite
- [OpenModelica](https://github.com/OpenModelica/OpenModelica) — Modelica-based environment for equation-based, acausal system modelling

### Electronics & PCB design

- [CuFlow](https://github.com/jamesbowman/cuflow) — experimental procedural PCB layout program
- [gerber2ems](https://github.com/antmicro/gerber2ems) — Python interface to openEMS for PCB trace simulation, taking Gerbers as input
- [pcbflow](https://github.com/michaelgale/pcbflow) — Python PCB layout and design package, based on CuFlow
- [PolymorphicBlocks](https://github.com/BerkeleyHCI/PolymorphicBlocks) — hardware description language for board-level design from reusable subcircuit generators
- [SKiDL](https://github.com/devbisme/skidl) — design electronic circuits in Python instead of a schematic editor

### Optimization

- [Pyomo](https://github.com/Pyomo/pyomo) — object-oriented algebraic modelling language in Python for structured optimization

### Visualization & mesh analysis

- [Blender Geometry Nodes](https://docs.blender.org/manual/en/latest/modeling/geometry_nodes/index.html) — node-based procedural geometry inside Blender
- [ParaView](https://github.com/Kitware/ParaView) — VTK-based analysis and visualization application for large simulation output
- [PyVista](https://github.com/pyvista/pyvista) — 3D visualization and mesh analysis for science and engineering, over VTK
- [VTK](https://github.com/Kitware/VTK) — the visualization and mesh processing toolkit that PyVista wraps

### Domain-specific

- [orlab](https://github.com/CameronBrooks11/orlab) — Python module for scripting OpenRocket, for simulation and computational workflows
- [RocketPy](https://github.com/RocketPy-Team/RocketPy) — 6-DOF trajectory simulation for high-power rocketry

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

You are welcome to fork the repository and add new tools and submit a pull request or open an issue detailing what you'd like to be added and why it fits the criteria.

Planned work for the list is tracked in [TODO.md](./TODO.md).

### Local Testing

From your repo root run:

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000 in your browser.

## Guidelines

- **Be respectful** — maintain a respectful and collaborative tone in all interactions.
- **Be clear** — ensure that your contributions are well-documented and clearly explained.
- **Be consistent** — follow the existing formatting and organizational structure.

## License

Distributed under the AGPL v3 License. See [LICENSE](./LICENSE) for more information.

## Acknowledgements

Inspired by [Awesome Lists](https://github.com/topics/awesome-lists) and [awesome](https://github.com/sindresorhus/awesome).

Thanks to all the open-source contributors and communities that make these tools possible.
