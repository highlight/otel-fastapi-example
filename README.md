# Python / OTel Quickstart

This repository is built by highlight.io. If you want to get started with a simple OpenTelemetry (OTel) backend with a cloud service, you can head over to [highlight.io](https://highlight.io). 

## Development Setup

### Prerequisites
- Python 3.8 or higher
- [Poetry](https://python-poetry.org/docs/#installation)

### Installation Steps
1. Clone the repository:
2. Configure your `HIGHLIGHT_PROJECT_ID` in `o11y.py`
3. Install dependencies:
   ```bash
   poetry install --no-root
   ```

4. Run the app:
   ```bash
   poetry run uvicorn main:app --reload
   ```