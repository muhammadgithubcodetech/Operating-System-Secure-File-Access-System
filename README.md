# Operating-System-Secure-File-Access-System
A simplified operating system simulation that enforces secure file access using user authentication, role-based permissions, and access control mechanisms. This project demonstrates key OS-level security principles such as user isolation, secure file handling, and controlled file operations.

Secure File Access System
=========================


How to Run the Project
----------------------
1. Open the project folder in any Python IDE. (Recommended: PyCharm)
2. [Optional] Change the file storage directory:
   - By default, all encrypted files are saved in the 'data/' folder.
   - You may change the `DATA_FOLDER` path in `files.py` to a custom directory of your choice.
3. Run the project by executing `GUI.py` from the `src/` folder.

   Example (in terminal or IDE):
   python GUI.py

Folder Structure
----------------
Secure_File_Access_System/
├── src/               # All Python source files
│   ├── GUI.py
│   ├── auth.py
│   ├── files.py
│   ├── encryption.py
│   └── logs.py
├── data/              # Runtime file storage (auto-created)
├── output/            # Optional: logs.txt and users.json (if separated)
├── docs/              # Report and presentation files
├── README.txt         # Project instructions

Dependencies
------------
This project uses only standard Python libraries (no installation required):
- tkinter
- hashlib
- json
- os
- datetime

Features
--------
- User login and registration with SHA-256 hashed passwords
- Role-based permissions (admin/user)
- File creation, viewing, and deletion with XOR encryption
- Access restriction by file ownership and role
- Timestamped logging of all user actions
- Admin functions: view logs, delete users, clear logs

Notes
-----
- Ensure the project is run from its root folder for proper file creation.
- All logs and user accounts will be generated automatically during use.
- GUI provides a safe interface to test OS-like operations without needing terminal commands.

Developed by: Muhammad Shah
GitHub: muhammadgithubcodetech
