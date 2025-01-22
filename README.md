# Python / OTel Quickstart

## Development Setup

### Prerequisites
- Python 3.8 or higher
- [Poetry](https://python-poetry.org/docs/#installation)

### Installation Steps
1. Clone the repository:
2. Configure your HIGHLIGHT_PROJECT_ID in `o11y.py`
3. Install dependencies:
   ```bash
   poetry install
   ```

4. Run the app:
   ```bash
   poetry run uvicorn main:app --reload
   ```