# Machine & Equipment Management System  
### (Bilingual: English–Persian)

---

## 🔹 Overview
This system provides a complete solution for managing machines, equipment, and maintenance records.  
It supports bilingual operation (English & Persian) and is suitable for factories, workshops, or construction companies that need to track equipment usage, maintenance schedules, and service history.

The system consists of:
- **Backend:** Django + Django REST Framework  
- **Desktop Client:** PyQt  
- **Database:** SQLite (easily switchable to PostgreSQL or MySQL)

---

## 🔹 Features
- Machine and equipment registration  
- Spare parts and maintenance record management  
- User authentication and role-based access control  
- RESTful API for external integration  
- Reporting and export to Excel/PDF  
- Bilingual interface (English & Persian)

---

## 🔹 Installation
### Requirements
- Python 3.10+
- pip
- Virtual environment (recommended)

### Steps
```bash
# 1. Clone repository
git clone https://github.com/your-username/machine-management-system.git

# 2. Enter project directory
cd machine-management-system

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run migrations
python manage.py migrate

# 5. Start server
python manage.py runserver
