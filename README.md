This was a simple form validator made to practice my JS skills. The main skill was using If/Else statements
in combination with Booleans to make sure users were filling out all the required fields for the form with
the correct information. Here are some things I learned or practiced along the way


HTML
- Used divs to create the container for the main form
- used other divs to separate each iput field with different types, id's, and requirments if necessary



CSS
- used very simple CSS to style the form container and all the input fields
- practiced using flex-box and properly aligning items



JS:
- used global variables to target necessary HTML elements mainly by getElementByID
- also used let variables to set initial value of false
- made use of checkValidity() method to determine true/false of form
- set conditional statements based on the forms validity
- also added statements to make sure passwords matched and used .style to adjust elements & indicate if fields were fileld correctly
- used if statement with 2 conditionals (x && y) to fully validate the form
- created a 'dummy' function to store the form data of the user to late be used for backend purposes (currently not using)
- With all functions, created a processFormData(event) to run our main functions when event listener 'submit' is executed.


This was a very simple JS project to follow along to.  It provided great practice for me. The main takeaway's were using conditional statements (maybe add turnary in future)
to validate form inputs. The other takewaway was building out the main functionality such as validateForm() and storeFormData()
to then be used in our processFormData() function. There was only one necessary event listener, however in the future I imaging 
I will be using many more.
