# CIA_JAVA_MINI_PROJECT

📚 Library Management System -Java

##PROJECT OUTLINE

a library management system created utilising Object-Oriented Analysis and Design principles. The GUI contains very little code, and the entities are also separated. It has a console-based user interface. The "Object Oriented Analysis and Design CS309" course is where this project was developed.



## Actors:
The actors include the following: 
* Librarian
* Checkout Clerk
* Borrower
* Administrator



![interface](https://user-images.githubusercontent.com/97155542/236445363-a39f0d7a-e103-45cc-be12-a8a8325d8508.png)


![interface2](https://user-images.githubusercontent.com/97155542/236435919-fd4681c7-f632-48e4-adf2-b7ab48dbe434.png)




## Project Working

## Use Cases
The second phase in use case analysis is to identify the tasks that each actor will have to perform with the system after identifying the players. Each activity is referred to as a "use case" since it illustrates a specific use of the system.

**In other words, only those use cases are listed that actors will need to do when they are using the system to solve the customer’s problem.** 

### Borrower:
* ❏ Search for items by title.
* ❏ ... by author.
* ❏ ... by subject.
* ❏ Place a book on hold if it is on loan to somebody else.
* ❏ Check  the  borrower’s  personal  information  and  list  of  books  currently
borrowed.

### Checkout Clerk:
* ❏ All the Borrower use cases, plus
* ❏ Check out an item for a borrower.
* ❏ Check in an item that has been returned.
* ❏ Renew an item.
* ❏ Record that a fine has been paid.
* ❏ Add a new borrower.
* ❏ Update a borrower’s personal information (address, telephone number etc.).

### Librarian:
* ❏ All of the Borrower and Checkout Clerk use cases, plus
* ❏ Add a new item to the collection.
* ❏ Delete an item from the collection.
* ❏ Change the information the system has recorded about an item.

### Administrator:
* ❏ Add Clerk.
* ❏ Add Librarian.
* ❏ View Issued Books History.
* ❏ View All Books in Library.

## How to Run the Project

**Step 1:** In the Netbeans Window, there is a tab named "Services" on the left. Select it. Then right click on JavaDB > Properties and    change database location to "Database" folder downloaded with this repository (its placed besides the "Project" folder).

**Step 2:** After that a database named LMS will show up under JavaDB tab. Now Right Click Databases > New Connection and select Java DB Network and click Next. 

   
**Step 3:** Provide the following database crendentials in the next popup and click Next.
  ```
  Host: localhost
  Port: 1527
  Database: LMS
  User Name: haris
  Password: 123
  
  **Step 4:**
Now just click Next for the rest of the windows. After all this the database connection is made. Make sure that you connect with the database before running the project by right clicking on the connection and selecting connect. Now you are ready to run the project!

## Note
The password for Administrative Functions is *lib*. The admin adds new clerks and librarian, then they both do the rest of the functions.



