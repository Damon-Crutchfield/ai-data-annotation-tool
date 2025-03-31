# AI Data Annotation Tool

A powerful tool for annotating and labeling data for AI model training and improvement.

## Features

- **AI Annotation**: Easily label and organize data for machine learning models.
- **User Authentication**: Secure login with OAuth2 authentication.
- **FastAPI Backend**: Efficient API to handle annotation requests.
- **Next.js Frontend**: Modern frontend with dynamic user interfaces.
- **Docker Support**: Dockerized for consistent development and deployment.
- **CI/CD**: Fully automated testing and deployment using GitHub Actions.

## Installation

### Backend

1. Clone the repository.

    ```bash
    git clone https://github.com/your-username/ai-data-annotation-tool.git
    cd ai-data-annotation-tool
    ```

2. Set up a virtual environment.

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install dependencies.

    ```bash
    pip install -r backend/requirements.txt
    ```

4. Run the backend.

    ```bash
    uvicorn backend.main:app --reload
    ```

### Frontend

1. Install Node.js dependencies.

    ```bash
    cd frontend
    npm install
    ```

2. Run the frontend.

    ```bash
    npm run dev
    ```

## Running with Docker

1. Build and start the services using Docker Compose.

    ```bash
    docker-compose up --build
    ```

2. The backend will be available at `http://localhost:8000`, and the frontend at `http://localhost:3000`.

## Tests

### Backend

1. Navigate to the backend folder.

    ```bash
    cd backend
    ```

2. Run tests.

    ```bash
    pytest
    ```

### Frontend

1. Navigate to the frontend folder.

    ```bash
    cd frontend
    ```

2. Run tests.

    ```bash
    npm run test
    ```

## CI/CD

This project uses GitHub Actions for continuous integration and deployment. Workflows are defined in the `.github/workflows` directory.

- **Backend CI**: Runs tests and builds the backend.
- **Frontend CI**: Runs tests and builds the frontend.
- **Deploy**: Deploys the application to your server or cloud platform.

## License

This project is licensed under the MIT License.
