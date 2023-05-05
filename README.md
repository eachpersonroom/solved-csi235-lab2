Download Link: https://assignmentchef.com/product/solved-csi235-lab2
<br>
<strong> </strong>Read and analyze the relational schemas listed below. For each one of the relational schemas find all nontrivial functional dependencies valid in the schemas.  Then, for each schema, explain which functional dependencies cause the redundancies (if any).

STUDENT(snumber, first-name, last-name, ccode)

A relational table STUDENT contains information about the students and the courses enrolled by the students. A course (ccode) is enrolled by more than one students (snumber) and each student enrols several course. Student number (snumber) uniquely identifies each students and course code (ccode) uniquely identifies each course. The first (first-name) and the last (last-name) names describe the students.

HOTEL(name, city, capacity, enumber, salary)

A relational table HOTEL contains information about the hotels and employees working in the hotels. A hotel is identified by a pair of attributes (name, city) and it is also described by the total number of rooms available (capacity). Each employee is identified by employee number (enumber) and it is described by a salary (salary).

WAREHOUSE(wname, address, part, quantity)

A relational table WAREHOUSE contains information about the names of warehouses (wname) located at the given addresses (address). Each warehouse is located at one address and there is only one warehouse at each address. Parts (part) are stored in a warehouse. A quantity of each part is determined by a value of attribute quantity.




<h3>LIBRARY(cnumber, title, price, isbn)</h3>

A relational table LIBRARY contains information about the books available from a library. Each copy of a book is uniquely identified by call number (cnumber). A book has one title (title) and one price (price). International system book number (isbn) is commonly used to uniquely identify a book.

Deliverables

A file solution1.pdf with the lists of nontrivial functional dependencies valid in each one of the relational schemas described above and with the explanations which functional dependencies cause the redundancies (if any).

<h2>Task 2</h2>

Perform the following steps and save the outcomes in a file solution2.pdf.

(1) Consider a relational schema R(A, B, C, D, E) and the following set of functional  dependencies valid in the schema,




<h3>{A ®B, C  ® A}</h3>




List all derivations of functional dependencies that lead to the identification of minimal keys. List all minimal keys valid in a relational schema. Note, that a schema can have more than one minimal key.




(2) Consider a relational schema R(A, B, C, D, E) and the following set of functional  dependencies valid in the schema,




<h3>{A ® E, E ® C, CD ® A}</h3>




List all derivations of functional dependencies that lead to the identification of minimal keys. List all minimal keys valid in a relational schema. Note, that a schema can have more than one minimal key.




(3) Consider a relational schema R(A, B, C, D, E) and the following set of functional  dependencies valid in the schema,




<h3>{D ® A, DA ® B, DE ® ABC}</h3>




List all derivations of functional dependencies that lead to the identification of minimal keys. List all minimal keys valid in a relational schema. Note, that a schema can have more than one minimal key.




<h2>Deliverables</h2>

A file solution2.pdf with the derivations of functional dependencies that lead to the identification of minimal keys in the steps listed above and with the lists of minimal keys and for each schema.




Note, that the “educated guesses” of minimal keys score no marks. You must provide the correct and complete derivations for each one of the minimal keys found.

<u>                                                                                                                                                </u>





