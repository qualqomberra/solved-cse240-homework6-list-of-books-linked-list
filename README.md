Download Link: https://assignmentchef.com/product/solved-cse240-homework6-list-of-books-linked-list
<br>
<strong>Reading</strong>: Chapter 2, Textbook Section 2.5.4 on linked list and Section 2.6 on parameter passing; Section 2.10 a case study on linked list operations; and sample code in lecture slides.

<strong>Preparation</strong>: Complete the multiple choice questions in the textbook exercise section. The answer keys can be found in the course Web site. These exercises can help you prepare for your weekly quiz and the exam. You are encouraged to read the other exercise questions and make sure you understand these questions in the textbook exercise section, which can help you better understand what materials are expected to understand after the lectures and homework on each chapter.

You are expected to do the majority of the assignment outside the class meetings.   Should you need assistance, or have questions about the assignment, please contact the instructor or the TA during their office hours.

You are encouraged to ask and answer questions on the course discussion board.  However, <strong>do not share your answers and code</strong> in the course discussion board.

<h1>Programming Assignment</h1>

<ol>

 <li>Based on the previous homework, you should implement hw06q1.c <strong>from scratch</strong>. The structure of this homework is similar to previous homework. In this homework, to do the same work in the previous homework, you must use <strong>a linked list</strong> instead of an array.</li>

 <li>You should use a struct ‘libraryRecord’ with elements for Book Title, Author’s Name, Book Type, Book Id, Aisle number in which the book should be kept. You will be completing a program that creates a list of books (a linked list of structs). It is a menu-driven program where the user is given the following options:

  <ol>

   <li>Add a new book to the list. When adding a new book to the list, the user is prompted for Book Title, Author Name, Book Type, Book Id and Aisle number of the book. The book should be added at the end of the list. If the book (name or ID) already exists in the list, then you should not add to the list. The book type is an enum type.</li>

   <li>Display the list of books from the linked list.</li>

   <li>Sort the list of books numerically by ID. The sorting should happen within the list. You should not create a new list (linked list of structs) of books having sorted books.</li>

   <li>Delete a book from the list. When deleting a book from the list, the user is prompted for Book ID only. The book should be removed from the list and the linked list structure should be preserved / restored afterwards. Attempting to delete a book who is not in the list should return 0. Otherwise, return 1 upon a successful removal of the record.</li>

  </ol></li>

</ol>




The behavior of save() in this assignment is the same as that of the previous homework.

However, you should modify it to new save() that handles a linked list instead of an array. Please refer to the specification of save() in the previous homework. You need to implement load() which is called at the start of the program. This function will read the saved file and fill in the linked list of structures. You need to read the file in the same order and manner that it is saved in save().




Expected output of each function:




<strong><u>Add</u></strong>

<strong><u>Display </u></strong>

(after adding 3 book details)

<strong> </strong>

<strong><u>Sort </u></strong><strong> </strong>

The books seen in display() output above are sorted in sort(). Use ‘d’ option to verify sorted result.

<strong><u>Delete </u></strong>




To verify that delete() worked as expected, use ‘d’ display option to display updated list.

<strong><u>Load </u></strong>

Notice the message given by load() “Books record loaded from Book_List.txt” at the top. To verify that load() worked as expected, use ‘d’ display option to display loaded list.

<strong> </strong>

<strong> </strong>