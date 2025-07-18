# Prescripto - Hospital Doctor Appointment Booking App

## Project Overview
Prescripto is a comprehensive full-stack web application designed to streamline the process of managing doctor appointments, edit profiles, online payments, and administrative tasks. It provides distinct, secure panels for users (patients), doctors, and administrators, ensuring a smooth and efficient healthcare experience.

## Live Demos
Experience the application live!

**Disclaimer :** if there is a network error i suggest wait for a few minutes and keep refreshing at ALL DOCTORS page to witness the full functionality of the application as the server is hosted on render's free tier instance, so it might take a few minutes to cold start the server as the server gets killed due to inactivity due to the constraints of free tier instance. 

* **User/Patient Interface:** [https://prescriptodoctorappointmentapp.netlify.app/]
* **Admin & Doctor Panel:** [https://prescriptoadmindoctorpanel.netlify.app/login]
    * **Admin Credentials:**
        * Email: `admin@prescripto.com`
        * Password: `admin12345`
          
## Repositories for the User Interface, Admin & Doctor Panels and Server 

* **User/Patient Interface:** [https://github.com/rohit-0604/Prescripto-User]
* **Admin & Doctor Panel:** [https://github.com/rohit-0604/Prescripto-Admin-Doctor]
* **Server:** [https://github.com/rohit-0604/Prescripto-Server]

## Architecture
This application follows a modern, decoupled architecture, consisting of three main components, each hosted in its own dedicated GitHub repository and deployed independently:

1.  **User Frontend:** Built with React (Vite) for intuitive patient-facing interactions, allowing users to browse doctors, book appointments, manage their profiles, view their appointments and manage their appointments.
2.  **Admin & Doctor Frontend:** Also built with React (Vite), providing powerful dashboards for administrators to manage the system (doctors) and for doctors to manage their appointments, profiles, and availability.
3.  **Backend API:** A robust Node.js/Express API that acts as the central data hub. It handles user authentication (JWT), business logic, data storage in MongoDB, and serves data securely to both frontend applications.


