 JavaScript Data Types - User Profile Demo

The following JavaScript **data types** are used:

| Data Type  | Description                              |
|------------|------------------------------------------|
| String     | Text data (`"Sowmiya Ravichandran"`)     |
| Number     | Numeric data (`21`)                      |
| Boolean    | True/false status (`true` for online)    |
| Array      | List of hobbies (`["Reading", ...]`)     |
| Object     | Location with city & country             |
| null       | Empty value to represent missing bio     |
| undefined  | Variable declared but not initialized    |


##  Features

- Shows user details in a neatly styled profile box.
- Uses `document.getElementById().textContent` to update HTML content.
- Handles special values like `null` and `undefined` safely.
- Simple layout using HTML and CSS.
- Beginner-friendly and fully commented.


### 1. Data Declaration

The script creates various variables to hold user data:

```js
let name = "Sowmiya Ravichandran";   // String
var age = 21;                        // Number
let isOnline = true;                // Boolean
let hobbies = ["Reading", "Cooking", "Traveling"]; // Array
let address = { city: "Coimbatore", country: "India" }; // Object
let bio = null;                     // Null
let score = 100;                    // Normally would be undefined

Displaying in HTML

JavaScript sets the values into HTML using:

document.getElementById("userName").textContent = " Name: " + name;

3. Special Handling

For null: Shows "Bio: Not added yet."

For undefined: Shows "Score: Not assigned yet." (if score is not given)
