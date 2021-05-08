# library-loopback4
Library management project backend work


## Tech used

	- docker environment
	- Vue 3
	- Loopback 4
	- mongoDb

## tables used

Student
	- id
	- fName
	- lName
	- email

Book
	- id
	- title
	- author
	- categoryId
	- ISBN
	- purchasedOn
	- edition

BookCategory
	- id
	- name

BookIssue
	- id
	- bookId
	- studentId
	- issueDate
	- returnDate
	- notes

