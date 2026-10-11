# Assignment 4. Forms and Validation

Name:Zharkyn
Group:IT-2502
Link:https://koqaa.netlify.app/
Part 1. Basic HTML Forms

### Task 0. Simple Contact Form
Create a basic contact form with Name, Email, Message and a Submit button. All fields must have `<label>`.

<img width="838" height="520" alt="image" src="https://github.com/user-attachments/assets/3464c0a8-c85e-4062-b1a8-f57cc50aa1ac" />


### Task 1. Form with HTML5 Validation
Add built-in validation attributes (`required`, `type`, `minlength`, `maxlength`) and test how the browser checks them.

<img width="789" height="480" alt="image" src="https://github.com/user-attachments/assets/1bd54287-4869-414c-862a-013a3ef896a4" />


Part 2. Bootstrap Forms

### Task 2. Bootstrap Form Styling
Recreate the contact form with Bootstrap classes, use the grid, add placeholders and helper text.

<img width="775" height="464" alt="image" src="https://github.com/user-attachments/assets/c7799364-20c4-43b1-ac43-70897d0ea071" />

### Task 3. Bootstrap Validation Styles
Use `is-valid` and `is-invalid` classes and show feedback messages under inputs. Tested with valid and invalid data.

<img width="786" height="464" alt="image" src="https://github.com/user-attachments/assets/06d49449-5daf-44c8-908a-3158e8429e44" />


Part 3. Advanced Form Project

### Task 4. Registration Form
Registration form with First Name, Last Name, Email, Password + Confirm Password, Gender (radio), Hobbies (checkboxes), Country (select), Submit and Reset. Made responsive with the Bootstrap grid, with HTML5 validation and Bootstrap feedback.

<img width="771" height="605" alt="image" src="https://github.com/user-attachments/assets/f8f80d2c-c5d7-49ea-9e96-5d1d780ae710" />


## Summary of my work

First I made a simple contact form in HTML and added validation attributes like `required`, `minlength` and `type="email"` (Task 1). Then I remade it with Bootstrap-style classes (`form-control`, `row`, `col-md-6`), but I did not add the Bootstrap library, I wrote this CSS myself in `css/style.css` (Task 2). In Task 3 I used JavaScript with `checkValidity()` to add `is-valid` and `is-invalid` classes and show feedback messages. In Task 4 I made the registration form with a password match check, a gender check and a reset button. I tested everything in the browser with valid and wrong data.
