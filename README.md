# 📝 Student Records Basic Data Manager

A simple Python console application to manage student names and their marks using basic array/list operations. This was a project for my first computer science course!

## ✨ Project Goal

The main goal of this project was to practice and demonstrate the five fundamental operations on data structures (specifically, Python lists, which act like dynamic arrays):

1.  **Insertion** (Adding new data)
2.  **Deletion** (Removing existing data)
3.  **Searching** (Finding data)
4.  **Updation** (Changing existing data)
5.  **Traversing** (Displaying all data)

## 🛠️ Technology Used

* **Language:** Python (3.x)

## 📁 How to Run the Program

1.  **Save the file:** Save the Python code as a file named `student_manager.py`.
2.  **Open Terminal/Command Prompt:** Navigate to the folder where you saved the file.
3.  **Execute the script:** Run the following command:

    ```bash
    python student_manager.py
    ```

4.  The program will start by asking you to input some initial student data, and then display the main menu.

## ⚙️ Program Features (Menu Options)

The program uses two parallel lists: `names` and `marks`. All operations ensure that the student's name and their corresponding mark stay linked together.

| Option | Operation | Description |
| :---: | :---: | :--- |
| **1** | **Insert** | Adds a new student and their mark at an index (position) specified by the user. |
| **2** | **Delete** | Removes a student's record using the index (position) provided by the user. |
| **3** | **Search** | Finds a student by name and prints their index and mark if found. |
| **4** | **Update** | Finds a student by name and allows the user to change their stored mark. |
| **5** | **Display** | Prints all current student records (index, name, and mark) in a list format. |
| **6** | **Exit** | Closes the program. |

## 🌟 Key Concepts Learned

* Using **separate lists** to manage related data (`names` and `marks`).
* The difference between adding to the end (`.append()`) and adding to a specific position (`.insert()`).
* Using the `try-except` block for basic **input validation** (checking if inputs are numbers).
* Using **loops** (`while` and `for`) for traversing and repetitive input.
* The importance of **matching indexes** when performing operations like deletion and update on parallel lists.

---
*Created by [Your Name] for [Course Name, e.g., CSC 101] - Fall [Year]*
