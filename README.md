# Online Train Ticket Booking System

The Online Train Ticket Booking System is designed to assist busy individuals who travel by train and lack time to visit the station to purchase tickets. This system enables users to reserve train tickets online from any location at any time. Users can log in, select their preferred train and class, make payments, and receive a soft copy of their ticket via email. Additionally, users can change their seats or classes within an hour of booking and provide feedback on their experiences.

### Key Features
- **User Registration -** Users can register and log in to access the system.
- **Train Schedule Check -** Users can view train schedules.
- **Ticket Booking -** Users can book tickets by selecting the training type and class.
- **Booking Modification -** Users can modify their seats and classes within an hour of booking.
- **Feedback System -** Users can leave feedback and reviews.

### Technologies Used
- **Frontend -** HTML, CSS
- **Backend -** PHP
- **Database -** MySQL
- **Local Server -** XAMPP

## How to Install and Run the Project

### Prerequisites
- **XAMPP**: Download and install from [Apache Friends](https://www.apachefriends.org/index.html).

### Installation Steps
1. **Clone the Repository**:
    ```sh
    git clone https://github.com/gitFerdo/Online-Train-Ticket-Booking-System.git
    ```
2. **Move to the Project Directory**:
    ```sh
    cd Online-Train-Ticket-Booking-System
    ```
3. **Start XAMPP**:
    - Open XAMPP Control Panel.
    - Start Apache and MySQL.

4. **Set Up the Database**:
    - Open phpMyAdmin from XAMPP Control Panel.
    - Create a new database named `railroad`.
    - Import the `railroad.sql` file located in the `database` folder.

5. **Configure the Database Connection**:
    - Open `config.php` file in the project directory.
    - Update the database credentials if necessary.

6. **Run the Project**:
    - Place the project folder in the `htdocs` directory of XAMPP.
    - Open a web browser and navigate to `http://localhost/Online-Train-Ticket-Booking-System`.

## Tests

### Running Tests
1. Navigate to the project directory:
    ```sh
    cd Online-Train-Ticket-Booking-System
    ```
2. Ensure XAMPP is running with Apache and MySQL services.
3. Use a testing framework or manually test the application by interacting with various features and ensuring proper functionality.

## How to Contribute to the Project

1. Fork the repository.
2. Create your feature branch:
    ```sh
    git checkout -b feature/YourFeature
    ```
3. Commit your changes:
    ```sh
    git commit -m 'Add some feature'
    ```
4. Push to the branch:
    ```sh
    git push origin feature/YourFeature
    ```
5. Open a pull request.
