# Calc Draw - Backend

This project is a backend implementation for a calculator inspired by the Apple iPad calculator. It features a responsive, user-friendly interface with FastAPI as the backend for handling calculations.

## Features

- **Dynamic expression evaluation** powered by FastAPI.
- Seamless integration with a React frontend for a smooth, interactive experience.
- Support for advanced mathematical expressions using MathJax rendering.

## Tech Stack

- **Backend:** FastAPI
- **Frontend:** React, Tailwind CSS (handled separately)
- **Math Rendering:** MathJax

## Getting Started

Follow the steps below to clone, install, and run the backend locally.

### Prerequisites

Ensure you have the following installed:
- Python 3.8+
- FastAPI
- uvicorn (ASGI server)

### Cloning the Repository

First, clone the repository from GitHub:

```bash
git clone https://github.com/your-username/smartCalc-backend.git
cd smartCalc-backend
```

### Installing Dependencies

Create a virtual environment and install the necessary dependencies:

1. Create a virtual environment:
   ```bash
   python3 -m venv venv
   ```

2. Activate the virtual environment:
   - For Linux/Mac:
     ```bash
     source venv/bin/activate
     ```
   - For Windows:
     ```bash
     .\venv\Scripts\activate
     ```

3. Install the dependencies from `requirements.txt`:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Application

To run the FastAPI backend locally, use the following command:

```bash
uvicorn main:app --reload
```

- The `--reload` flag ensures the server reloads automatically when code changes are detected.

The API will be available at [http://127.0.0.1:8999](http://127.0.0.1:8999). 

### Additional Notes

- Make sure to integrate the backend with your React frontend to handle the math calculations seamlessly.
- Modify environment variables as needed for deployment configurations.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

### Frontend Link : [https://github.com/saiSribhashyam/smartCalc-Frontend.git](https://github.com/saiSribhashyam/smartCalc-Frontend.git)
