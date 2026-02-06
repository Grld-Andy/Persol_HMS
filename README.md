# Hospital Management System (DotNet MVC)
This is a Hospital Management System built using DotNet MVC. It provides a comprehensive solution for managing patients, medications, and hospital queues. The system is designed with a focus on the needs of medical staff, offering features for doctors, nurses, records clerk, lab personnels, administrators and other healthcare professionals.

## Features
1. Authorization: Secure access to the system is ensured with user authentication.
2. Patient Management: Efficiently manage patient records, including medical history and current medications.
3. Drug Management: Easily add and update drug prescriptions for patients.
4. Queue Management: Streamlined queue management for doctors to attend to patients in an organized manner.
5. Lab Integration: Seamless integration with lab services, tracking test results and diagnoses.
6. Departmental Access Control: Different access levels for various departments within the hospital.

## Getting Started

### Prerequisites
Visual Studio or any other preferred code editor.

### Installation

#### Using .NET CLI
DotNet 6 SDK must be installed

1. Clone the repository -> ```git clone https://github.com/Grld-Andy/Persol_HMS.git```
2. Open the project in Visual Studio.
3. Run the application -> ```dotnet watch run```.

#### Using Docker
1. Build the dockerfile with ```docker build -t persol_hms .```
2. Run the image using ```docker run -p 8080:80 persol_hms```

## Usage
1. Navigate to the application URL.
2. Log in using your credentials.
    ### Default login credentials
    - Username -> Password
    - Records_01 -> Records_01
    - Nurse_01 -> Nurse_01
    - Doctor_01 -> Doctor_01
    - Lab_01 -> Lab_01
    - Pharmacy_01 -> Pharmacy_01
    - Cashier_01 -> Cashier_01
    - Admin_01 -> Admin_01

3. Access different modules based on your role (Doctor, Lab, etc.).
4. Manage patients, medications, and appointments through the user-friendly interface.

## Contributing
Contributions are welcome! If you have any ideas, improvements, or bug fixes, feel free to open an issue or create a pull request.


### Auth Pages
Login Page
![Login Page](/wwwroot/images/login_page.png)

Register Page
![Register Page](/wwwroot/images/register_page.png)