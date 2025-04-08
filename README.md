# 🏥 Hospital Management Web Application – Secure PHP Project

> A secure hospital management platform developed with PHP, MySQL, HTML, and CSS, ensuring confidential handling of patient and administrative data. Built as part of the *Secure Web Development* course at Euromed University of Fez.

---

## 📁 Project Structure

```
📂 hospital-management-secure/
├── accueil/
│   ├── interface_home.php
│   ├── interface_home.css
│   ├── service_home.php
│   ├── service_home.css
│   ├── contact_home.php
│   ├── contact_home.css
│   └── about_home.php
├── auth/
│   ├── connexion.php
│   ├── connexion.css
│   ├── logout.php
│   ├── registration_admi.php
│   └── registration_admi.css
├── admin/
│   ├── interface_admi.php
│   ├── gestion_admi.php
│   ├── gestion_med_admi.php
│   ├── gestion_pat_admi.php
│   ├── ajouter_admi.php
│   ├── modifier_admi.php
│   ├── supprimer_admi.php
│   └── afficher_admi.php
├── medecin/
│   ├── ajouter_med.php
│   ├── modifier_med.php
│   ├── supprimer_med.php
│   └── afficher_med.php
├── patient/
│   ├── ajouter_pat.php
│   ├── modifier_pat.php
│   ├── supprimer_pat.php
│   ├── afficher_pat.php
│   ├── dossier_medical.php
│   ├── dossier_medical_admi.php
│   └── paiement_pat.php
├── rendezvous/
│   ├── rendez-vous.php
│   ├── rendez-vous.css
│   ├── rendez_vous_pat.php
│   └── rendez_vous_med.php
├── services/
│   ├── Chirurgie_home.php
│   ├── Gastro-entérologie.php
│   ├── MédecineGénérale.php
│   ├── ObstétriqueetGynécologie.php
│   ├── Pédiatrie_home.php
│   ├── Urgence_home.php
│   ├── cardiologie_home.php
│   ├── orthopédgie_home.php
│   └── otorhinolaryngologie.php
├── styles/
│   ├── gestion_pat_admi.css
│   ├── ajouter_pat.css
│   ├── modifier_pat.css
│   └── specialite.css
├── includes/
│   └── database.php
├── images/
│   ├── *[all image files like home.jpg, signin1.jpg, about1.jpg, etc.]*
```

---

## ⚙️ Features

### ✅ Authentication
- Secure login and logout
- Admin registration form
- Role-based access (Admin / Patient)

### 🩺 Admin Functionalities
- Manage patients, doctors, and admins (CRUD)
- View and assign medical records
- Schedule and manage appointments

### 👨‍⚕️ Patient Functionalities
- Book, view, and cancel appointments
- Access personal medical records
- Make payments (payment module in progress)

### 🖼️ Public Pages
- Welcome interface and department showcase
- Hospital services with images
- Contact form and about section

---

## 🔐 Security Implementations

- Role-based access control
- Input validation and session protection
- Minimal database exposure through `database.php`
- Clean separation between admin and patient roles

---

## 🛠️ Technologies

- **Frontend**: HTML5, CSS3
- **Backend**: PHP
- **Database**: MySQL
- **Styling**: Custom CSS
- **Security**: PHP sessions, form validation

---

## 🚀 How to Run the Project

1. Clone the repository
2. Import the database using the provided SQL dump (if applicable)
3. Configure your local `database.php` connection
4. Host the project on XAMPP / WAMP / Local Apache Server
5. Open `interface_home.php` in your browser

---

## 👩‍💻 Author

**Maroua Maliki**  
Cybersecurity Engineering Student – Euromed University of Fez  
Project supervised by **Prof. Ahmed Amamou**
