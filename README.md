# TechSage

TechSage is a technology blog where we share articles, news and tutorials about the world of technology, programming, trends and more.

## Requirements

- **Django**: Web framework for fast and scalable development.
- **django-htmx**: HTMX integration with Django for partial page refresh without reloading.
- **django-taggit**: To add tags to articles.
- **Markdown**: To support content written in Markdown in articles.
- **pytest** and **pytest-django**: For project testing.
- **black**, **flake8** and **mypypy**: Tools to make sure the code complies with quality and formatting standards.

## Instalación

1. **Clone the repository**.

   ```bash
   git clone https://github.com/leiberbertel/TechSage_blog.git
   cd techsage
   ```

2. **Configure the virtual environment**

   ```bash
   python -m venv venv
   source venv/bin/activate  # En Linux/macOS
   venv\Scripts\activate     # En Windows
   ```

3. **Install the dependencies**.

   ```bash
   pip install -r requirements.txt
   ```

4. **Configurar las variables de entorno**

   ```
   SECRET_KEY='your-secret-key'
   DATABASE_URL='postgres://user:password@localhost:5432/techsage'
   ```

5. **Perform migrations**

   ```bash
   python manage.py migrate
   ```

6. **Create a superuser (optional)**

   ```bash
   python manage.py createsuperuser
   ```

7. **Running the development server**

   ```bash
   python manage.py runserver
   ```

   Access the application at [http://127.0.0.1:8000](http://127.0.0.1:8000).

## Tests

```bash
pytest
```

## Contributions

Contributions are welcome! If you want to improve the project, please follow these steps:

1. Make a fork of this repository.
2. Create a branch for your feature (`git checkout -b feature/new-feature`).
3. Make your changes and add tests if necessary.
4. Commit your changes (`git commit -m 'Added new feature'`).
5. Push the changes to your repository (`git push origin feature/new-feature`).
6. Open a Pull Request.

## License

This project is licensed under the MIT license. See the [LICENSE](LICENSE.txt) file for more details.
