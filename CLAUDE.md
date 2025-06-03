# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a simple GitHub Pages website hosted at `shamsheeryousaf.github.io`. The project consists of a single HTML file that displays a dynamic greeting showing the current day of the week.

## Architecture

- **index.html**: Main HTML page with embedded JavaScript that dynamically updates the greeting based on the current day
- Uses vanilla JavaScript with `Date().getDay()` to determine the current day
- No build process required - direct HTML/JS deployment to GitHub Pages

## Development

Since this is a static HTML page hosted on GitHub Pages, changes are deployed automatically when pushed to the main branch. No build commands, test frameworks, or development servers are configured.