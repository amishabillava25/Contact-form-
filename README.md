Task 6:Create a Contact Form and Validate Inputs Using JavaScript.

In this project, I developed a responsive Contact Form using HTML, CSS, and JavaScript to collect user information such as name, email, and message. The main goal was to design an interactive form with proper client-side validation that ensures users provide correct and complete information before submitting.

I started by creating the HTML structure, which included labeled input fields for name and email, a textarea for the message, and a submit button. I also added placeholder text and separate <div> elements below each field to display error messages dynamically whenever the user enters invalid or empty data. This made the form user-friendly and organized.

Next, I used CSS to make the form visually appealing and responsive. I centered the form on the page using Flexbox, applied smooth borders, padding, and shadows to improve the overall layout, and used different colors to indicate form states. For example, error messages were displayed in red, while the success message appeared in green. The button was also styled with hover effects to give a modern and interactive look. The CSS part ensured that the form is both clean and easy to use on different screen sizes, including mobile devices.

After designing the layout, I added JavaScript to handle form validation. I wrote a validation script that runs whenever the user clicks the submit button. The script first prevents the default form submission using event.preventDefault() to ensure validation happens before sending data. It then checks three main conditions:

The name field is not left empty.

The email field is filled and matches the correct email pattern using a regular expression (regex).

The message field contains some text.

If any field fails validation, an appropriate error message appears below that input, guiding the user to correct it. If all inputs are valid, the script hides all error messages and displays a success message saying “✅ Your message has been submitted successfully!” The form fields are then reset automatically using form.reset().

I also tested different edge cases — such as empty fields, incorrect email formats like “abc@” or “abc@gmail,” and spaces-only inputs — to make sure the form validation works correctly in all situations. The validation process ensures that only properly formatted data is accepted, improving both user experience and form reliability.

Through this project, I gained practical experience in form handling, input validation, and DOM manipulation using JavaScript. I also learned how to use regular expressions for checking email patterns and how to provide real-time feedback to users with error and success messages. Additionally, this project helped me understand how HTML, CSS, and JavaScript work together to create interactive web components. Overall, this was an excellent exercise in front-end web development, combining design, logic, and validation techniques into one functional mini project.
