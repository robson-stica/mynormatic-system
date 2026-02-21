# MyNormatic
### Corporate Management System (Academic Mini-ERP Prototype)

## 📌 Overview
MyNormatic is a web-based corporate management system developed during a Software Engineering academic project in partnership with the company Normatic.

The platform was designed as a functional prototype of a corporate digital ecosystem, integrating operational workflows, role-based access, data interaction and intelligent assistance modules within a single unified interface.

Rather than a simple academic interface, the system was conceived as a **mini ERP prototype**, focused on process organization, internal management simulation and future scalability for real enterprise environments.

---

## 🎯 Project Objective
The main objective of MyNormatic is to centralize corporate information, workflows and interactions for different organizational roles such as administrators, managers, collaborators and clients.

The system simulates how a real company could operate through a structured digital platform, allowing visualization of internal processes, operational data and intelligent support tools.

It was built to demonstrate:
- Corporate system architecture concepts
- Role-based access logic
- Data-driven interface behavior
- Future ERP integration potential

---

## 🏢 Corporate Ecosystem Structure
MyNormatic represents a simulated corporate ecosystem with multiple user perspectives:

- 👑 Administrator (Admin)
- 👨‍💼 Managers (Gestores)
- 👷 Collaborators (Colaboradores)
- 🤝 Clients (Clientes)

Each role interacts with different sections of the platform, reflecting a real organizational environment.

---

## ⚙️ Core System Features

### 🖥️ 1. Integrated Corporate Interface
- Centralized dashboard environment
- Modular navigation between system sections
- Corporate-oriented UI and UX
- Structured panels for operational visualization

### 📊 2. Excel-Based Data Simulation (Database Prototype)
The system uses Excel files as a simulated data layer:
- Dynamic data loading via JavaScript
- Login validation through spreadsheet records
- Safe academic database simulation
- No dependency on external database servers

This approach was intentionally adopted to replicate real data-driven behavior in an academic environment.

---

## 🔐 System Access & Authentication (Official Demo Credentials)

MyNormatic uses a **hybrid authentication model**:
- Fixed role-based authentication (Admin, Manager, Collaborator)
- Dynamic client authentication via Excel database (`base_dados.xlsx`)

All credentials and data are fictional and used exclusively for academic and demonstration purposes.

---

### 👑 Administrator Access (Full System Control)
- User Type: Admin  
- Login: admin  
- Password: 123  

Access Scope:
- Full system navigation
- Administrative modules
- System management panels
- Complete ecosystem overview

---

### 👨‍💼 Manager (Gestor) Access
- User Type: Gestor  
- Login: gestor 
- Password: 123  

Access Scope:
- Management dashboards
- Operational visualization
- Internal workflow modules
- Strategic interface sections  

Note: Manager authentication is role-based and validated primarily by password logic.

---

### 👷 Collaborator (Colaborador) Access
- User Type: Colaborador  
- Login: colaborador
- Password: 123  

Access Scope:
- Internal operational features
- Workflow interaction modules
- Employee system perspective

---

### 🤝 Client Access (Excel Database Authentication)
Client accounts are dynamically validated through the Excel data layer (`base_dados.xlsx`).

Valid demo client accounts:
- Login: beta | Password: 12345678  
- Login: metalparts | Password: 12345678  
- Login: delta | Password: 12345678  
- Login: tratofer | Password: 12345678  
- Login: gama | Password: 12345678  

Recommended account for richer data visualization:
- **metalparts**

---

### 📌 Technical Authentication Note
- Administrator, Manager and Collaborator roles use fixed authentication logic inside the system
- Client access is dynamically loaded from the Excel database
- No real corporate database is used (academic prototype)
- All credentials are fictional and safe for public repository use

---

## 🤖 AI Integration (Dual Intelligent Agents)

MyNormatic includes two AI-assisted modules designed to simulate intelligent corporate support tools:

### 🧠 Normatic Assistant
- General system guidance
- Contextual interaction
- Platform assistance simulation

### 🛠️ Technical Consultant AI
- Technical support simulation
- Process-oriented suggestions
- Operational assistance logic

### 🔒 AI Demo Mode (Security-Oriented)
For security and best practices:
- API keys are NOT stored in the repository
- AI runs in optional demo mode
- The system remains fully functional without AI activation

To enable AI locally (optional):
```js
localStorage.setItem('GEMINI_API_KEY_NORMATIC','YOUR_API_KEY');
localStorage.setItem('GEMINI_API_KEY_CONSULTANT','YOUR_API_KEY');
