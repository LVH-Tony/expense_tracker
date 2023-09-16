# Rumi Press Expense Tracker

Developed a Django-based expense tracker app to facilitate Rumi Press in managing book distribution expenses efficiently. Hosted on Heroku, the app ensures data security and offers insightful visual reports.

## Solution

Leveraging Django-Heroku, I created a secure and user-friendly expense tracker app for Rumi Press. The app, hosted on Heroku, facilitates easy management of book distribution expenses through intuitive interfaces and visual reports, enhancing business decision-making.

## Approach

1. Requirement analysis
2. Database design using Django
3. Application scaffolding through Django Admin
4. Business process customization for automation
5. Visual reporting feature integration
6. Deployment on Heroku utilizing Django-Heroku
7. Conducted bug testing
8. Documentation and showcasing on Coursera portfolio

## Getting Started

### Prerequisites

- Python 3.8 or newer
- Django 4.0.4

### Installation

Clone the repository to your local machine:

```bash
git clone https://github.com/lvh-tony/expense_tracker.git
```

Navigate to the project directory:

```bash
cd rumi-press-expense-tracker
```

Install the required packages:

```bash
pip install -r requirements.txt
```

### Configuration

Configure the `settings.py` file for hosting based on your Django project setup before running the project.

### Running the Project

Execute the following commands in sequence to run the project:

```bash
python manage.py collectstatic
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

Access the app at [http://127.0.0.1:8000/](http://127.0.0.1:8000/).

## Contributing

Feel free to fork the project, open a pull request, or report any issues you encounter.

## Credits

Special thanks to [Parth971](https://github.com/Parth971) for the guidance and assistance.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
