# Django Tailwind Boilerplate

Welcome to the Django Tailwind Boilerplate repository! This boilerplate serves as a starting point for your Django web application, integrated with the powerful Tailwind CSS library for effortless and responsive UI development. 

## Packages Used

- django-tailwind - Simplifies the integration of Tailwind CSS into Django projects, allowing seamless usage of Tailwind CSS classes within Django templates.

- django-compressor - Optimizes and compresses static assets, such as CSS and JavaScript files, to improve website performance by reducing file sizes and minimizing HTTP requests.

- python-decouple - helps you to organize your settings so that you can change parameters without having to redeploy your app.

## Getting Started

1. Clone the repository: git clone https://github.com/ruslansco/django_tailwind_boilerplate.git

2. Create and activate virtual environment:
   
   ```shell
   python -m venv env
   ```

3. Install the Python dependencies: 
   
   ```shell
   pip install -r requirements.txt
   ```

4. Install *Tailwind CSS* dependencies, by running the following command:
   
   ```shell
   python manage.py tailwind install
   ```

5. Create .env file in the root directory and add your keys for the following:
   
   ```env
   SECRET_KEY=
   ALLOWED_HOSTS=
   DEBUG=
   DB_ENGINE=
   DB_NAME=
   ```

6. Run: python manage.py runserver

## Customization

Configurations: Adjust the Django project settings in conf/settings.py to match your requirements.

Templates: Modify or create new HTML templates in the templates/ directory to build your application's UI.

Static Assets: Customize or add your own static assets (stylesheets, JavaScript files, images, etc.) in the 'theme' directory.

Additional Dependencies: Install and integrate additional Django packages or third-party libraries as needed.

## Contributing

Contributions are welcome! If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. Feel free to use and modify it for your own purposes.

## Acknowledgements

We would like to express our gratitude to the Django and Tailwind CSS communities for their excellent frameworks and libraries that made this boilerplate possible.

If you have any questions or need further assistance, please feel free to reach me. Happy coding!


