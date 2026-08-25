# cellular-automaton-web-app

![Status: Work in Progress](https://img.shields.io/badge/status-work%20in%20progress-orange)

**Cellular Automaton** is a Python/FastAPI web application for configuring and running Conway's Game of Life simulations. It validates user parameters, runs the simulation, generates an animated GIF, and provides the result for download without persistently storing simulation data.

## Previous Version

This project is an evolution of my first Cellular Automaton project, which was developed as a local Python/Jupyter Notebook implementation. The original project generated Game of Life simulations and GIF visualizations using fixed parameters and was an opportunity to learn the fundamentals of cellular automata and Python-based simulation.

The original project is available here:

[CellularAutomaton](https://github.com/aaronmkwong/CellularAutomaton)

This version builds on that foundation by restructuring the simulation into a more modular application and introducing a FastAPI backend, parameter validation, compute limits, rate limiting, GIF generation, and a web-based interface. The goal is to improve both the software architecture and my backend development skills while turning the original local experiment into a reproducible web application.