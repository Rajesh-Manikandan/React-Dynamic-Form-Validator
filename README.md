## 1. Dynamic Form Validator
Objective: Develop a user registration form with dynamic validation to ensure that all required fields are filled out correctly and that email addresses are in the correct format.

**Challenge:** Implement dynamic validation to provide real-time feedback to users as they fill out the form, indicating any errors or missing information.

**Skills tested:** Form handling, input validation, state management

**Difficulty:** Easy

### Tasks
1. Create a user registration form UI with fields for username, email, and password.
2. Implement dynamic validation to check for required fields and valid email format.
3. Display error messages next to the corresponding input fields for invalid entries.
4. Add a submit button to trigger form submission.
5. Integrate form submission with a mock API call (simulated delay).
6. Display a success message upon successful registration.

### Hints

* Use React useState hook to manage form state and input values.
* Utilize regular expressions or a library like Yup for input validation.
* Conditionally render error messages based on input validation results.
* Disable the submit button if there are validation errors.
* Use a loading spinner or message to indicate form submission in progress.