# Event Calendar in Django

A simple event calendar application built with Django. Users can create, view, update, and delete events on a calendar interface. Follow the setup instructions to get started quickly. Includes an admin panel for easy management of events. Created by [SHESHU45](https://github.com/SHESHU45).

## How To Setup

Follow these steps to set up the Event Calendar application:

1. Clone the repository:
   ```
   git clone https://github.com/SHESHU45/event-calender.git
   ```

2. Navigate to the project directory:
   ```
   cd event-calendar
   ```

3. Set up a virtual environment (optional but recommended):
   ```
   python -m venv venv
   ```

4. Activate the virtual environment:
   ```
   venv/bin/activate
   ```

5. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

6. Apply migrations to create the necessary database tables:
   ```
   python manage.py makemigrations
   python manage.py migrate
   ```

7. Create a superuser account to access the admin panel (optional):
   ```
   python manage.py createsuperuser
   ```

8. Run the development server:
   ```
   python manage.py runserver
   ```

9. Access the application by visiting `http://127.0.0.1:8000/` in your web browser.

## Usage

Once the application is set up and running, you can perform the following actions:

- **Create Events:** Click on the "+" button to add a new event. Fill in the details such as title, description, date, and time.
  
- **View Events:** Events are displayed on the calendar interface. Click on a specific date to view the events scheduled for that date.
  
- **Update Events:** Double-click on an event to edit its details.
  
- **Delete Events:** Click on the "X" button to delete an event.

## Admin Panel

Access the Django admin panel by visiting `http://127.0.0.1:8000/admin/` and log in using the superuser credentials created earlier. From the admin panel, you can manage users, events, and other application data.

## Credits

This Event Calendar application was created by [SHESHU45](https://github.com/SHESHU45).
