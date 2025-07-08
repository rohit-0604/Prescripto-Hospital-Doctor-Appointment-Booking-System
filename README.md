# Prescripto - Online Doctor Appointment Booking App

## Project Overview
Prescripto is a comprehensive full-stack web application designed to streamline the process of managing doctor appointments, edit profiles, online payments, and administrative tasks. It provides distinct, secure panels for users (patients), doctors, and administrators, ensuring a smooth and efficient healthcare experience.

## Live Demos
Experience the application live!

* **User/Patient Interface:** [https://prescriptodoctorappointmentapp.netlify.app/]
* **Admin & Doctor Panel:** [[https://prescriptoadmindoctorpanel.netlify.app/login](https://prescriptoadmindoctorpanel.netlify.app/login)]
    * **Admin Credentials:**
        * Email: `admin@prescripto.com`
        * Password: `admin12345`

## Architecture
This application follows a modern, decoupled architecture, consisting of three main components, each hosted in its own dedicated GitHub repository and deployed independently:

1.  **User Frontend:** Built with React (Vite) for intuitive patient-facing interactions, allowing users to browse doctors, book appointments, manage their profiles, view their appointments and manage their appointments.
2.  **Admin & Doctor Frontend:** Also built with React (Vite), providing powerful dashboards for administrators to manage the system (doctors) and for doctors to manage their appointments, profiles, and availability.
3.  **Backend API:** A robust Node.js/Express API that acts as the central data hub. It handles user authentication (JWT), business logic, data storage in MongoDB, and serves data securely to both frontend applications.
