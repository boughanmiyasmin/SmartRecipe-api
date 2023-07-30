# SmartRecipe-api: REST API with Django

## Description
This project is a fully functioning REST API built with Django that provides various features like user authentication, object creation, filtering, sorting, uploading and viewing images, and much more. The API is developed following best practice principles and Test Driven Development (TDD) to ensure robustness and maintainability.

## Features
- User Authentication: The API allows users to register, login, and access protected endpoints using token-based authentication.
- Creating Objects: Users can create objects through API endpoints, which are stored in the database.
- Filtering and Sorting Objects: The API supports filtering and sorting objects based on different parameters for better data manipulation. (under development)
- Uploading and Viewing Images: Users can upload images through the API, and it provides endpoints to view the uploaded images. (under development)
- Docker and Docker-Compose Setup: The project includes instructions on how to set up the development environment using Docker and Docker-Compose for easy deployment and scalability.
- GitHub Actions: GitHub Actions are configured to run linting and unit tests automatically on each push, ensuring code quality.
- Django Test Framework: The project includes unit tests using the Django Test Framework to verify the functionality of the API.
- Test Driven Development (TDD): The development process follows the TDD approach, writing tests before implementing new features.
- Media Files Handling: The API is equipped to handle media file uploads effectively using Django's media handling capabilities.(under development)
- Customization of Django Admin: The Django Admin interface is customized to provide a more tailored and user-friendly experience. (under development)
- Postgres Database: The API is configured to use a Postgres database for data storage and retrieval, ensuring data integrity and performance.

## Installation and Setup
1. Clone the repository
2. Navigate to the project directory: `cd SmartRecipe-api`
3. Set up Docker and Docker-Compose on your system following the installation guide: [Docker](https://docs.docker.com/get-docker/) and [Docker-Compose](https://docs.docker.com/compose/install/)
4. Create a virtual environment (recommended) and install dependencies:
   ```bash
   python -m venv env
   source env/bin/activate   # On Windows, use: env\Scripts\activate
   pip install -r requirements.txt
   ```
6. Apply database migrations: `python manage.py migrate`
7. Run the development server: `python manage.py runserver`

## Usage
- Access the API documentation at `http://localhost:8090/api/docs/` to explore available endpoints and their functionalities.
- Use tools like `curl`, Postman, or any API client to interact with the API.

## Testing
To run the unit tests, execute the following command:
```bash
python manage.py test
```

## Contributing
Contributions to the project are welcome! If you find any issues or want to add new features, please feel free to submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgments
The development of this API was heavily influenced by various open-source projects, tutorials, and the Django community.
