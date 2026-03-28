# utokriet - FB Account Creator

## Overview
A Python command-line tool for creating Facebook accounts using Filipino and RPW (Remotely Placed Workers) names with temporary email addresses.

## Project Structure
- `utokriet.py` - Main script (1751 lines), contains all logic

## Tech Stack
- **Language**: Python 3.12
- **Key Libraries**:
  - `faker` - Fake data generation
  - `fake-useragent` - Random user agent strings
  - `beautifulsoup4` - HTML parsing
  - `requests` - HTTP requests
  - `rich` - Terminal UI (panels, prompts, colors)

## Running the App
The app runs as an interactive CLI tool in the console workflow.

```
python3 utokriet.py
```

## Features
- Generate Filipino or RPW names (male/female/mixed)
- Create temp emails using yuennix.site or weyn.store domains
- Register Facebook accounts with customizable passwords
- Multi-threaded account creation
- Results saved to file

## Workflow
- **Start application**: `python3 utokriet.py` (console output type)
