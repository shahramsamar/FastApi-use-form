# FastAPI Exercise Using Form

A simple **FastAPI** project demonstrating the handling of form submissions. This application shows how to process form data, validate it, and send dynamic responses based on form inputs.

## Features

- **Form Handling**: Handle form submissions with FastAPI.
- **Data Validation**: Validate form data using Pydantic models.
- **Dynamic Responses**: Generate responses based on submitted form data.
- **FastAPI**: Fast web framework for API development.

## Getting Started

Follow these steps to set up and run the project locally.

### Prerequisites

- **Python 3.7+**: Python version 3.7 or higher is required.
- **Git**: Git for cloning the repository.
- **Virtual Environment**: Set up a Python virtual environment to isolate dependencies.

### Installation

1. **Clone the repository**:

    ```bash
    git clone https://github.com/shahramsamar/Fastapi-Exercise-UsingForm.git
    cd Fastapi-Exercise-UsingForm
    ```

2. **Create and activate a virtual environment**:

    - On macOS/Linux:

    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

    - On Windows:

    ```bash
    python -m venv venv
    venv\Scripts\activate
    ```

3. **Install dependencies**:

    ```bash
    pip install -r requirements.txt
    ```

4. **Run the application**:

    ```bash
    uvicorn main:app --reload
    ```

5. **Access the app**:

    Open your browser and visit [http://localhost:8000](http://localhost:8000).

### Usage

- **Submit Form**: Submit form data via the form page to interact with the application.
  
- **Dynamic Response**: The app processes the form data and sends back a response dynamically based on the submitted values.

## Project Structure

- **`main.py`**: FastAPI app with form handling logic.
- **`schemas.py`**: Pydantic models for form data validation.
- **`templates/`**: HTML templates for form rendering.

## Technologies Used

- **FastAPI**: A modern, fast web framework for building APIs with Python.
- **Pydantic**: Used for data validation and serialization.
- **Jinja2**: Template engine for rendering HTML forms.

## Contributing

Feel free to fork, modify, and submit pull requests for bug fixes or improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

For more detailed API documentation, visit [http://localhost:8000/docs](http://localhost:8000/docs) after running the app.
![Alt](https://repobeats.axiom.co/api/embed/eabe6508a91fa38b4ace0060919094363916f544.svg "Repobeats analytics image")
