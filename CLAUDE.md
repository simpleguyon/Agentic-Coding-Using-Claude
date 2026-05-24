# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Common Commands
- Install dependencies: `pip install -r expense-tracker/requirements.txt`
- Run the application: `python expense-tracker/app.py`
- Run tests: `pytest`

## Architecture and Structure
The project is a Flask-based expense tracker application located in the `expense-tracker/` directory.

- `expense-tracker/app.py`: Main entry point and route definitions.
- `expense-tracker/database/`: Database utility functions for SQLite connection and initialization (`db.py`).
- `expense-tracker/templates/`: HTML templates for the frontend.
- `expense-tracker/static/`: CSS, images, and other static assets.
- `expense-tracker/requirements.txt`: Python package dependencies.

The application currently uses a basic route structure with several placeholders for future implementation (e.g., logout, profile, expense management).
