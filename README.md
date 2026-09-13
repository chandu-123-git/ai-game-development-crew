# AI Game Development Crew

An AI-powered game development workflow that uses multiple specialized agents to design, generate, and review a playable 2D game using Python and Pygame.

## Overview

This project uses CrewAI to coordinate three specialized AI agents:

1. Game Designer – Converts a game idea into a structured game design document.
2. Senior Python Game Developer – Generates a complete, runnable Pygame script based on the design.
3. QA Engineer and Code Reviewer – Reviews the generated code for errors, completeness, playability, and improvements.

The generated game is then built for the browser using Pygbag and served through a public ngrok URL.

## Features

- AI-generated game concepts and mechanics
- Multi-agent collaboration using CrewAI
- Automated game code generation
- Code review and quality checks
- Python and Pygame-based game development
- Browser deployment using Pygbag
- Public game access using ngrok
- Interactive gameplay with keyboard or mouse controls

## Technologies Used

- Python
- CrewAI
- Google Gemini 2.5 Flash
- Pygame
- Pygbag
- Pyngrok
- Google Colab

## Project Workflow

```text
User Game Idea
      ↓
Game Designer Agent
      ↓
Game Design Document
      ↓
Senior Python Game Developer Agent
      ↓
Complete Pygame Code
      ↓
QA Engineer and Code Reviewer Agent
      ↓
Reviewed Game Code
      ↓
Pygbag Build
      ↓
Browser-Based Game
