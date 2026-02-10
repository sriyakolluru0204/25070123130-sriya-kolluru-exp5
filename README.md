Topic: Title implementation dictionary in Python

Algorithm
A. Update Product Price

Algorithm:

Initialize a dictionary named product with product names as keys and prices as values.

Display the product dictionary to show the original prices.

Update the price of a specific product using:
product["Book"] = "55 Rupees"

Display the updated product dictionary to show the modified price.

B. Search Student Marks

Algorithm:

Initialize a dictionary named student with student names as keys and their marks as values.

Accept a name from the user and store it in the variable name.

Search for the name using:
student.get(name, "Student not found")

If the name exists, display the student’s marks. Otherwise, display "Student not found".

C. User Login Validation

Algorithm:

Initialize a dictionary named users with usernames as keys and passwords as values.

Accept input from the user for username and password.

Validate the login by checking:
users.get(username) == password

If the condition is true, display "Login successful".
Otherwise, display "Invalid username or password".

D. Find Highest Scorer

Algorithm:

Initialize a dictionary named student with student names as keys and their marks as values.

Find the student with the highest marks using:
topper = max(student, key=student.get)

Retrieve the topper’s marks using:
student[topper]

Display the name of the topper along with their marks.

conclusion:
**Conclusion:**

From the above tasks, we understood how dictionaries in Python are used to store and manage data efficiently using key value pairs.
We learned how to update values, search for specific keys, validate user credentials, and identify the maximum value in a dictionary. 
These operations demonstrate the flexibility and practical applications of dictionaries in real world scenarios such as product management, student records, 
login systems, and result analysis. Overall, this exercise improved our understanding of dictionary manipulation and data handling in Python.
