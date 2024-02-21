# Django Capital Cities Project
This Django project provides a web-based UI for users to modify a database by uploading countries and their corresponding capital cities, and also pull information from it by calling the country.
The project is also meant to be an starter structure that can be freely be modified in the future to be some sort of playground to get your hands-on and get confident enough to use of the basic GIT commands such as **add**, **commit** and **push**
## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/topogoogles/capital_cities.git
2. Navigate to the project directory:
    ```bash
    cd capital_cities
3. Create a virtual environment and activate it:
    ```bash
    conda create --name capital_cities_env python=3.8
4. Activate the conda environment
    ```bash
    conda activate capital_cities_env
5. Install the required packages using conda:
    ```bash    
    conda install --file requirements.txt
6. Apply the database migrations:
    ```bash
    python manage.py migrate
7. Start the development server:
    ```bash
    python manage.py runserver
8. Access the application at http://localhost:8000

## Usage
To upload countries and their capital cities, navigate to the upload page and submit the necessary information.
To pull information for a specific country, use the provided web-based UI to search for the country and view its corresponding capital city.
>**Technologies Used**
 - Python
 - Django
 - HTML
 - CSS
## Project Structure
The project follows the standard Django application structure with the following key components:
countries app: Contains the models, views, and templates for managing countries and their capital cities.
## Contributing
Contributions are welcome! Please follow the contribution guidelines.
