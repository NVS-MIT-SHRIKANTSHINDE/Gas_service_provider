**Gas Service Provider Web Application**

This Django application aims to provide consumer services for gas utilities, offering customers the ability to submit service requests online, track their status, and access their account information. It also equips customer support representatives with tools to efficiently manage requests and provide support.

### Features
1. **Service Requests**
   - Customers can submit service requests online.
   - They can select the type of service request, provide detailed information, and attach files if necessary.

2. **Request Tracking**
   - Customers can track the status of their service requests.
   - They can view the current status, submission timestamp, and resolution timestamp.

### Application Structure
The Django application follows a structured codebase to ensure scalability, maintainability, and readability. Key components include:

- **Models:** Define the structure of the database, including models for users, service requests, and customer support interactions.

- **Views:** Handle user interactions, processing requests, and rendering appropriate templates.

- **Templates:** HTML templates for rendering user interfaces, including forms for service request submission and request tracking.

- **Forms:** Define forms for user input validation and processing, ensuring data integrity.

- **URLs:** Map URLs to views, enabling navigation within the application.

- **Admin Interface:** Utilize Django's built-in admin interface for easy management of application data by administrators.

### Installation
To install and run the Gas Service Provider Web Application, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/NVS-MIT-SHRIKANTSHINDE/Gas_service_provider.git
   ```

2. Navigate to the project directory:
   ```
   cd Gas_service_provider
   ```

3. Create a virtual environment (optional but recommended):
   ```
   python3 -m venv myenv
   ```

4. Activate the virtual environment:
   - On Windows:
     ```
     myenv\Scripts\activate
     ```
   - On macOS and Linux:
     ```
     source myenv/bin/activate
     ```

5. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

6. Apply migrations to set up the database:
   ```
   python manage.py migrate
   ```

7. Run the development server:
   ```
   python manage.py runserver
   ```

8. Access the application in your web browser at `http://localhost:8000`.

### Implementation
![Screenshot 1](https://github.com/NVS-MIT-SHRIKANTSHINDE/Gas_service_provider/raw/main/web_application/images/Screenshot%202024-04-19%20014347.png)
![Screenshot 2](https://github.com/NVS-MIT-SHRIKANTSHINDE/Gas_service_provider/raw/main/web_application/images/Screenshot%202024-04-19%20014433.png)
![Screenshot 3](https://github.com/NVS-MIT-SHRIKANTSHINDE/Gas_service_provider/raw/main/web_application/images/Screenshot%202024-04-19%20014452.png)
![Screenshot 4](https://github.com/NVS-MIT-SHRIKANTSHINDE/Gas_service_provider/raw/main/web_application/images/Screenshot%202024-04-19%20014516.png)
![Screenshot 5](https://github.com/NVS-MIT-SHRIKANTSHINDE/Gas_service_provider/raw/main/web_application/images/Screenshot%202024-04-19%20014529.png)
![Screenshot 6](https://github.com/NVS-MIT-SHRIKANTSHINDE/Gas_service_provider/raw/main/web_application/images/Screenshot%202024-04-19%20014603.png)
![Screenshot 7](https://github.com/NVS-MIT-SHRIKANTSHINDE/Gas_service_provider/raw/main/web_application/images/Screenshot%202024-04-19%20014638.png)
![Screenshot 8](https://github.com/NVS-MIT-SHRIKANTSHINDE/Gas_service_provider/raw/main/web_application/images/Screenshot%202024-04-19%20014704.png)

### Bonus Points
The Django application codebase is structured following best practices to ensure clarity, modularity, and ease of maintenance. Key considerations include:
- Modularization of code into reusable components.
- Clear separation of concerns between models, views, and templates.
- Consistent naming conventions and coding style.
- Proper use of Django's built-in features for authentication, form handling, and database management.
- Documentation and comments to aid understanding and future development.

For any further inquiries or assistance, please refer to the [Gas Service Provider GitHub repository](https://github.com/NVS-MIT-SHRIKANTSHINDE/Gas_service_provider) or contact the project maintainer.
