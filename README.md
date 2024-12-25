##### Name: ZOYA FATIMA
##### Company: CODTECH IT SOLUTIONS
##### ID: CT08DS571
##### Domain: PYTHON PROGRAMMING
##### Duration: 12 DEC 2024 TO 12 JAN 2025
##### Mentor: SRAVANI 

# **OVERVIEW OF THE PROJECT**

## PROJECT: **LIBRARY MANAGEMENT SYSTEM**

### **Description:**  
The Library Management System is a Python-based application designed to manage resources such as books, magazines, and DVDs in a library. The system supports functionalities like adding new items, borrowing and returning resources, searching for items, and managing overdue fines. It is an efficient tool for library administrators to streamline their operations.

### **Objectives:**  
1. Build a simple and effective library management solution using Python.  
2. Enable users to manage library resources such as books, magazines, and DVDs.  
3. Facilitate borrowing, returning, and inventory tracking functionalities.  
4. Provide search capabilities to locate items by title, author, or category.  
5. Implement overdue fine calculations for returned items.

### **Technologies Used:**  
- **Programming Language:** Python  
- **Libraries:** Standard Python libraries for file handling, string manipulation, and console interaction.  

### **Key Activities:**  
1. **Design and Planning:**  
   - Create a structured program with modules for adding, borrowing, returning, and searching items.  
2. **Development:**  
   - Build functions to handle core functionalities.  
   - Implement input validation to ensure data accuracy.  
3. **Testing:**  
   - Test for scenarios like invalid input, insufficient stock, and empty searches.  
4. **Documentation:**  
   - Provide detailed instructions and examples for using the system.

### **Key Features and Example Outputs:**

#### **1. Add New Items**  
Allows administrators to add resources to the library.  

**Input:**  
```
Enter your choice (1/2/3/4/5/6): 1
Enter the title: To Kill a Mockingbird
Enter the author: Harper Lee
Enter the category (e.g., book, magazine, DVD): Book
```

**Output:**  
```
Item 'To Kill a Mockingbird' added to the library.
```

#### **2. Borrow Items**  
Enables users to borrow resources from the library.  

**Input:**  
```
Enter your choice (1/2/3/4/5/6): 2
Enter the title of the item to borrow: To Kill a Mockingbird
Enter the borrower's name: John Doe
```

**Output:**  
```
Item 'To Kill a Mockingbird' borrowed by John Doe. Due date: 2024-01-06
```
If the item is unavailable:  
```
Item 'To Kill a Mockingbird' is currently not available.
```

#### **3. Return Items**  
Handles returning of borrowed resources and updates the inventory.  

**Input:**  
```
Enter your choice (1/2/3/4/5/6): 3
Enter the title of the item to return: To Kill a Mockingbird
```

**Output(On Time Return):**  
```
Item 'To Kill a Mockingbird' returned successfully.
Returned on time. No fine.
```
**Output(Late Return):**  
```
Item 'To Kill a Mockingbird' returned successfully.
Late return! You have a fine of Rs 15.00 for 3 overdue days.
```
If no borrowed record exists:
```
No borrowed record found for 'Unknown Book'.
```

#### **4. View All Items**  

**Input:**  
```
Enter your choice (1/2/3/4/5/6): 4
```

**Output(With items):**  
```
Library Collection:
Title: To Kill a Mockingbird, Author: Harper Lee, Category: Book, Status: Borrowed
Title: 1984, Author: George Orwell, Category: Book, Status: Available
```
**Output(Without items):**  
```
The library is empty.
```

#### **5. Search for Items**  
Search for resources by title, author, or category.  

**Input (by title):**  
```
Enter your choice (1/2/3/4/5/6): 5
Enter the title or author to search for: Harper
```

**Output(With matches):**  
```
Search Results:
Title: To Kill a Mockingbird, Author: Harper Lee, Category: Book, Status: Borrowed
```
**Output(No matches):**  
```
No items match your search.
```

#### **6. Exit the Program**  
**Input:**  
```
Enter your choice (1/2/3/4/5/6): 6
```

**Output:**  
```
Exiting the Library Management System. Goodbye!
```
