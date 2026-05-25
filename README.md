📚 Library Management System (Tkinter GUI Project)

A simple yet powerful Library Management System built using Python Tkinter.
It provides a graphical interface to manage books efficiently with features like add, update, delete, search, and persistent file storage.

🚀 Features
    ➕ Add new books with validation
    ✏️ Update existing book details
    ❌ Delete books easily
    🔍 Search books by Book ID
    📋 View all books in a table (Treeview)
    💾 Automatic data saving to file (books.txt)
    📂 Auto-load data on startup
    🚫 Prevent duplicate Book IDs
    🖥️ Simple and user-friendly GUI
    
🧰 Tech Stack
    🐍 Python 3.x – Core programming language
    🖼️ Tkinter – GUI framework (built-in)
    📊 ttk Treeview – Table-based data display
    💾 File Handling – .txt file for data storage

📁 Project Structure
    Library-Management-GUI/
    │
    ├── main.py                # Main Tkinter application
    ├── books.txt              # Auto-generated data file
    ├── library.png            # Project logo/banner
    ├── requirements.txt       # Dependencies file
    ├── README.md              # Project documentation
    
📦 requirements.txt
    # Library Management System
    # No external dependencies required

    # Python Standard Libraries Used:
    # tkinter, ttk, messagebox, file handling


⚙️ How to Run the Project
    1️⃣ Clone the repository
    git clone https://github.com/your-username/library-management-gui.git
    2️⃣ Move into project folder
    cd library-management-gui
    3️⃣ Run the application
    python main.py

    
🖥️ Application Layout
    📥 Input Section → Enter Book ID, Title, Author, Year
    📋 Table Section → Displays all stored books
    🔘 Action Buttons → Add, Update, Delete, Search, Exit

    
🔄 Functional Workflow
  ➕ Add Book
      Enter book details
      Click Add
      Data is saved in table + file
  ✏️ Update Book
      Enter Book ID
      Modify fields
      Click Update
  ❌ Delete Book
      Enter Book ID
      Click Delete
  🔍 Search Book
      Enter Book ID
      Click Search (highlights record)

      
💾 Data Storage
    Data is stored in books.txt
    Automatically loads when app starts
    Ensures persistent storage without database
    
📈 Future Improvements
    🌐 Convert into FastAPI backend system
    🗄️ Add MySQL / MongoDB database
    🖥️ Improve UI with modern Tkinter styling
    📊 Add analytics dashboard (most issued books)
    👤 Add login/authentication system
    🌍 Convert into web app (Streamlit / React frontend)

    
👨‍💻 Author:
    Tavprasad Singh
    🐍 Python Developer | DSA Learner | ML Enthusiast

⭐ Support
    If you like this project:
        ⭐ Star the repository
        🍴 Fork it
        🚀 Improve and contribute
