# 📚 SmartLib

**SmartLib** is a Software Engineering group project — a **self-service library application** that allows users to borrow and return books using their mobile devices.  

The goal of SmartLib is to modernize the traditional library experience by enabling contactless book management through a mobile app and automated backend services.

---

## 🧭 Table of Contents

- [Project Overview](#project-overview)
- [Application Description](#application-description)
- [Key Features](#key-features)
- [Technologies Used](#technologies-used)
- [Business Logic](#business-logic)
- [Possible Problems and Solutions](#possible-problems-and-solutions)
- [Team Structure](#team-structure)
- [Project Management](#project-management)
- [Git Workflow](#git-workflow)
- [License](#license)

---

## 🧩 Project Overview

### 📱 What is the application?

SmartLib is a **self-service library system**.  
Users can enter the library, scan a book using their **Android phone**, and borrow it directly — without librarian interaction.

**Main functionality:**
- 30-day borrowing period.
- Automatic email notifications for overdue books.
- Late fees of **15 PLN/day**, automatically charged from the linked payment card.
- Online registration and login.
- Backend panel for adding and managing books.
- Statistics available for librarians.
- User interface with search and catalog features.

---

## 🖼️ Application Description

### Librarian Views
1. Login
2. Book Catalog (with remove option)
3. Add New Book
4. [More to be defined...]

### User Views
1. Login
2. Registration
3. Book Catalog
4. Borrow / Scan Book
5. My Borrowings
6. [More to be defined...]

---

## ⚙️ Technologies Used

- **Frontend:** .NET MAUI (Android mobile app)
- **Backend:** .NET MAUI / C# (integrated backend services)
- **Database:** MySQL
- **Server:** Localhost setup
- **Version Control:** Git & GitHub
- **Communications:** Trello, Discord

---

## 🧠 Business Logic

SmartLib’s backend handles the main library operations:

- Adding new books  
- Removing books  
- Fetching book lists (with filters)  
- Borrowing and returning books  
- Sending reminder emails for returns  
- Registering new users (email, name, card details)  
- Deleting users  
- Verifying emails and payment cards  

---

## 💡 Possible Problems and Solutions

| Problem | Possible Solution |
|----------|-------------------|
| Overdue books not returned | Automatic daily email reminders |
| Unpaid fines | Auto-charge via saved card |
| Book inventory synchronization | Regular database consistency checks |
| Network or server failure | Local caching and retry mechanisms |

---

## 👥 Team Structure

### 🧱 Backend Team
| Name | Role |
|------|------|
| Dawid Daraż | Manager |
| Adrian Cydejko | Developer |
| Szymon Choiński | Developer |
| Asia Dagil | Developer |
| Michał Deptuła | Developer |
| Mateusz Durka | Developer |
| Danila Filipau | Developer |
| Jakub Gankowski | Developer |

### 🎨 Frontend Team
| Name | Role |
|------|------|
| Szymon Credo | Manager |
| Natalia Bardadyn | Developer |
| Olimpia Dejko | Developer |
| Szymon Doba | Developer |
| Karol Dziuba | Developer |
| Dawid Filipek | Developer |
| Franek Gotkowski | Developer |
| Olek Grzegrzułka | Developer |
| Karol Jurkewicz | Developer |

### 🧍 HR
| Name | Role |
|------|------|
| Piotr Czarnocki | Manager |

---

## 🗂️ Project Management

The team uses:
- **GitHub** for version control and collaboration  
- **Trello** for task tracking and sprint planning  

---

## 🌿 Git Workflow

Below is the standard workflow for working on SmartLib:

```bash
# Pull the latest version
git pull

# Create your own branch
git switch -c [your_branch_name]

# Stage all changes
git add .

# Commit with a clear message
git commit -m "[Describe what you did]"

# Push your branch to GitHub
git push origin [your_branch_name]

