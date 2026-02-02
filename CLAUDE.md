# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

A browser-based reaction time game built as a single self-contained HTML file (`reaction-game.html`). No build tools, dependencies, or package manager. Open the file directly in a browser to run.

## Architecture

Everything lives in `reaction-game.html` — HTML structure, CSS (in `<style>`), and JavaScript (in `<script>`) are all inline. The game uses a simple state machine with four states: `idle`, `waiting`, `ready`, and `result`. Key functions: `startGame()`, `tooEarly()`, `measureReaction()`, `createConfetti()`.
