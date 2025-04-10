# FastAPI Project Starter

This is a starter template for a FastAPI project.

This uses `fastapi`. It is set up to listen to `post` requests on port `3000`.

Modify the `play` function in `play.py` to write your bot code.

## Prerequisites

- Python 3.8 or higher is required for this project. You can install it using [pyenv](https://github.com/pyenv/pyenv) or download it from the [official Python website](https://www.python.org/downloads/).

## Setup

1. Create and activate a virtual environment:

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:

   ```bash
   uvicorn main:app --port 3000 --reload
   ```

4. Access the application at `http://127.0.0.1:3000`.

## License

This project is licensed under the MIT License.
