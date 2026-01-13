
## Task 1: Reading a File with Exception Handling

### Objective
To read the contents of a text file safely while handling possible runtime errors.

### Functionality
- Opens a file named `sample.txt` in read mode.
- Reads and prints each line from the file.
- Removes extra whitespace using the `strip()` method.
- Handles errors gracefully using exception handling.

### Exception Handling
- **FileNotFoundError**: Displays an error message if `sample.txt` does not exist.
- **Generic Exception**: Catches and displays unexpected errors.

### Output
- Prints file contents if the file exists.
- Displays an error message if the file is missing.


## Task 2: Writing, Appending, and Reading Data from a File

### Objective
To demonstrate writing user input to a file, appending additional data, and finally
reading the complete file content.

### Functionality
1. Takes user input and writes it to `output.txt`.
2. Appends additional user-provided text to the same file.
3. Reads and displays the final content of the file.

### File Operations Used
- **Write Mode (`w`)**: Creates or overwrites `output.txt` and writes user input.
- **Append Mode (`a`)**: Adds new content without deleting existing data.
- **Read Mode (`r`)**: Reads and displays the entire content of the file.

### Output
- Confirms successful writing and appending of data.
- Displays the final content of `output.txt`.


## How to Run the Programs
1. Ensure Python 3.x is installed.
2. Place the Python file(s) in the same directory.
3. Open a terminal or command prompt.
4. Run the program using:
   ```bash
   python filename.py
