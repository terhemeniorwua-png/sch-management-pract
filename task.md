Project: Student Management Dashboard
Objective

Build a web application that allows a school administrator to manage students using JavaScript.

You must not use any framework (React, Vue, Angular, etc.). Use only:

HTML
CSS (or Tailwind CSS if you want)
JavaScript
JSONPlaceholder API for practice with Fetch
Features
Part 1: Student Class (OOP)

Create a Student class.

Each student should have:

name
id
age
course
email
grade

Methods:

displayInfo()
updateGrade(newGrade)
Part 2: Store Students

Create an array called

let students = [];

Every new student object should be pushed into this array.

Part 3: Add Students

Create a form.

Inputs:

Name
Age
Course
Email
Grade

When submitted:

Create a new Student object.
Generate an ID automatically.
Push it into the array.
Display it on the page.
Part 4: Display Students

Use:

map()

to display all students inside cards.

Example

-----------------------
Name: Philip
ID: 1001
Course: JavaScript
Grade: A
-----------------------
Part 5: Search

Create a search box.

The administrator should be able to search by:

Name
ID

Use:

find()
Part 6: Filter

Add buttons

All

Grade A

Grade B

Grade C

Use

filter()
Part 7: Statistics

Display

Total Students

Average Grade

Number of A Students

Number of B Students

Number of C Students

Use

reduce()

where appropriate.

Part 8: Sorting

Buttons

Sort by Name

Sort by Grade

Sort by Age

Use

sort()
Part 9: Delete Student

Each card should have

Delete

button.

Use

filter()

to remove the student.

Part 10: Edit Grade

Each card should have

Edit Grade

Update the student's grade.

Part 11: JSON

Create at least 10 students as plain JavaScript objects.

Convert them to JSON

JSON.stringify()

Then convert them back

JSON.parse()

Display the parsed data.

Part 12: Fetch API

Use

https://jsonplaceholder.typicode.com/users

Display

Name
Email
Company

Also fetch

https://jsonplaceholder.typicode.com/posts

Display

Title
Body
Part 13: POST Request

Create a form.

When submitted

fetch(url,{
    method:"POST"
})

Send

{
name,
email,
course
}

Display the returned response.

Part 14: PATCH Request

Update only

email

using

PATCH
Part 15: PUT Request

Replace an entire student record.

Part 16: DELETE Request

Delete one record.

Display a success message.

Part 17: Error Handling

Wrap every request inside

try{

}catch(error){

}

Display

Loading...

Success

Failed
Part 18: Async/Await

Every API request must use

async

await

No .then().

Part 19: DOM Manipulation

Practice:

querySelector()
querySelectorAll()
getElementById()
innerHTML
textContent
createElement()
appendChild()
remove()
classList.add()
classList.remove()
Bonus Challenges

If you finish everything above, try these:

Add a dark mode toggle.
Highlight students with grade A in green.
Confirm before deleting a student.
Add pagination (e.g., show 5 students per page).
Add a loading spinner while fetching data.
Prevent duplicate student IDs.
Validate the form so no field is left empty.
Skills You'll Practice

By completing this project, you'll reinforce:

Variables and data types
Objects and arrays
Classes and methods
Array methods (map, filter, find, reduce, sort)
JSON (stringify and parse)
Fetch API
HTTP methods (GET, POST, PATCH, PUT, DELETE)
async / await
try...catch
DOM manipulation
Event handling
Form validation

This project is challenging enough to tie together the topics you've learned while still being manageable. If you can build it without following a tut