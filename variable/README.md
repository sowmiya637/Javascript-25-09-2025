#  Personalized Greeting Web Page using JavaScript
- If the input is empty, it shows an error message in red.


### ➤ HTML:
- `<input>` field to get user's name.
- `<button>` to trigger the greeting.
- `<p>` tag to display the output.

### ➤ JavaScript:
- Reads input value using `document.getElementById("username").value`.
- Checks if the name is **not empty**.
- Updates the paragraph with a message using `.textContent`.
- Changes text color if input is invalid (red) or valid (dark gray).

### ➤ CSS:
- Styled input, button, and output message.
- Uses `:hover` for button effects.
- Font, spacing, colors are all customized for a clean UI.

---

##  Example Output
If name = "Sowmiya", it shows:

Hello, Sowmiya! Welcome to the site.

If input is empty:

Please enter your name!



