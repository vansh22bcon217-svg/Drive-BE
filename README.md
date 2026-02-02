# File Management System

A **Google Drive–like File Management System** built using Java and ReactJS for managing, uploading, downloading, and sharing files efficiently.

---

## Overview

This project simulates a cloud-based file management system where users can:

* Upload, download, and organize files in folders
* Share files with others
* Move files to Trash and restore them
* Maintain file versioning and metadata

The system uses a **full-stack approach** with a Java backend and ReactJS frontend.

---

## Features

* **User Authentication:** Secure login and registration system.
* **File Upload/Download:** Upload files with type and size validation.
* **Folder Management:** Create, rename, and organize files in folders.
* **Trash Management:** Move files to trash and restore deleted files.
* **File Sharing:** Share files with specific users with view/edit permissions.
* **Responsive UI:** Clean and intuitive interface built with ReactJS.
* **File Metadata:** Store metadata like size, type, date, and owner in database.
* **Search & Sort:** Search files by name, type, or date.
* **Secure Storage:** Files stored securely on server with database maintaining metadata.

---

## Tech Stack

* **Frontend:** ReactJS, HTML5, CSS3, JavaScript
* **Backend:** Java (Spring Boot / Core Java)
* **Database:** MySQL
* **Build Tool:** Maven / Gradle
* **Version Control:** Git & GitHub
* **API:** RESTful APIs for file operations

---

## Project Structure

```
├── backend/             # Java backend code
├── frontend/            # ReactJS frontend code
├── database/            # SQL scripts for tables
└── README.md
```

---

## Installation

1. **Clone the repository:**

```bash
git clone https://github.com/yourusername/file-management-system.git
```

2. **Setup Database:**

* Create a MySQL database
* Run SQL scripts in `database/`

3. **Run Backend:**

```bash
cd backend
mvn spring-boot:run
```

4. **Run Frontend:**

```bash
cd frontend
npm install
npm start
```

---

## How to Use

1. Register as a new user
2. Login with your credentials
3. Upload files or create folders
4. Share files with other users
5. Move files to trash and restore as needed

---

## Contributing

Contributions are welcome! Please fork the repository and create a pull request.

---

## License

This project is licensed under the MIT License.

---

## Contact

* **Developer:** Vansh Upveja
* **Email:** [vanshupveja.06@gmail.com](mailto:vanshupveja.06@gmail.com)
* **LinkedIn:** [Vansh Upveja](https://www.linkedin.com/in/vansh-upveja-115036250/)
