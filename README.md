# Target Account Matching API (Flask)

## Setup Instructions

1. **Clone the repo** or download the ZIP.
2. **Create virtual environment** (optional ):
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows use venv\Scripts\activate
   ```
3. **Install dependencies**:
   ```
   pip install -r requirements.txt
   ```
4. **Run the app**:
   ```
   flask run
   ```

## API Endpoints

- `POST /login` - Authenticate user and return JWT
- `GET /accounts` - Return companies with match scores (JWT required)
- `POST /accounts/<id>/status` - Update target status (JWT required)
