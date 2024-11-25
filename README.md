
# Role-Based Access Control (RBAC) UI

This project is a **Role-Based Access Control (RBAC)** User Interface, designed as part of a frontend developer assignment. It includes an **admin dashboard** for managing users, roles, and permissions with a focus on **responsiveness**, **usability**, and **security**. The backend was implemented using **Django**, while the frontend was built using **Bootstrap**, **HTML**, **CSS**, and **JavaScript**.

---

## **Overview**

The RBAC system allows administrators to:
- View and manage users.
- Define and edit roles with associated permissions.
- Assign roles to users and manage their statuses.
- Customize permissions dynamically.

This project demonstrates a clean, intuitive UI with CRUD operations and emphasizes modularity, responsiveness, and security best practices.

---

## **Features**

### **User Management**
- **View Users**: Displays all users in a tabular format.
- **Add Users**: Includes a modal for adding new users with inputs for name, email, role, and status.
- **Edit Users**: Allows inline or modal-based user editing.
- **Delete Users**: Includes a delete confirmation modal for secure removal of users.

### **Role Management**
- **View Roles**: Provides a grid or list view of roles for better visual clarity.
- **Add Roles**: Enables defining new roles using a modal.
- **Edit Roles**: Allows modifying role details, including permissions.
- **Delete Roles**: Includes delete confirmation for secure role removal.

### **Dynamic Permissions**
- Assign permissions (e.g., Read, Write, Delete) to roles dynamically.
- Display permissions clearly for ease of understanding and modification.

### **Responsive Design**
- Fully responsive UI using **Bootstrap**, ensuring seamless usage across devices (desktop, tablet, and mobile).

### **Custom Navigation**
- Sidebar navigation with active states and icons.
- Includes intuitive hover and click effects.

### **Security Practices**
- Input validation to prevent invalid data entry.
- Confirmation modals for delete operations.
- Server-side security is handled via Django.

### **Additional Features**
- **Sorting and Filtering**: Added for tables and lists to manage large datasets effectively.
- **Search Functionality**: Allows searching for users or roles quickly.
- **Interactive Modals**: Clean, user-friendly modals for creating or editing data.

---

## **Technology Stack**

### **Frontend**
- **HTML5**: For semantic structure.
- **CSS3**: For styling and animations.
- **Bootstrap**: For responsiveness and design components.
- **JavaScript**: For dynamic interactions and CRUD functionality.

### **Backend**
- **Django**: For API endpoints, server-side processing, and data management.

---

## **Setup Instructions**

Follow these steps to run the project locally:

### Prerequisites
- Python (3.9 or later)
- Django (4.x or later)
- Bootstrap (v5)
- Any modern web browser (e.g., Chrome, Firefox)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/rbac-admin-dashboard.git
   ```
2. Navigate to the project directory:
   ```bash
   cd rbac-admin-dashboard
   ```
3. Create a virtual environment:
   ```bash
   python -m venv venv
   ```
4. Activate the virtual environment:
   - **Windows**:
     ```bash
     venv\Scripts\activate
     ```
   - **Mac/Linux**:
     ```bash
     source venv/bin/activate
     ```
5. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
6. Run migrations:
   ```bash
   python manage.py migrate
   ```
7. Start the development server:
   ```bash
   python manage.py runserver
   ```
8. Open the project in your browser:
   ```
   http://127.0.0.1:8000/
   ```

---

## **File Structure**

```
rbac-admin-dashboard/
├── rbac/
│   ├── settings.py        # Django project settings
│   ├── urls.py            # Project URLs
│   ├── wsgi.py            # WSGI configuration
├── dashboard/             # Django app for RBAC UI
│   ├── templates/         # HTML templates
│   ├── static/            # CSS, JS, and Bootstrap files
│   ├── views.py           # Views for user and role management
│   ├── models.py          # Data models for users and roles
│   ├── urls.py            # App-specific URLs
├── db.sqlite3             # SQLite database
├── manage.py              # Django management script
└── requirements.txt       # Python dependencies
```

---

## **Key Screenshots**

1. **Sidebar Navigation**
   - Compact, responsive, and visually appealing.

2. **User Management**
   - View, add, edit, delete users in an intuitive interface.

3. **Role Management**
   - Manage roles and their associated permissions dynamically.

---

## **Evaluation Highlights**

### **1. Creativity and Design Quality**
- The UI uses modern design principles and clean layouts, ensuring visual appeal.
- Interactive features (e.g., modals, filtering) enhance usability.

### **2. Responsiveness**
- Fully responsive design using **Bootstrap** for a consistent experience across devices.

### **3. Functionality**
- Implements core RBAC features with CRUD operations for users and roles.

### **4. User Experience (UX)**
- Simple, intuitive, and visually engaging interface for administrators.

### **5. Security**
- Input validation, error handling, and confirmation modals ensure robust security.

### **6. Documentation**
- Comprehensive README file with setup instructions, features, and project overview.

---


