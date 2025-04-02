# Student Data Filter

## Overview
This is a simple Python application that reads student data from a YAML file and provides functionality to display all students and filter students based on a minimum GPA.

## Features
- Load student data from a YAML file.
- Display all students with their details.
- Filter students based on a specified minimum GPA.

## Requirements
- Python 3.x
- PyYAML library

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/student-data-filter.git
   cd student-data-filter
   ```
2. Install dependencies:
   ```sh
   pip install pyyaml
   ```

## Usage
1. Ensure you have a `students.yaml` file with student data in the same directory.
2. Run the application:
   ```sh
   python app.py
   ```
3. The script will display all students and prompt you to enter a minimum GPA to filter students.

## File Structure
```
student-data-filter/
│── app.py           # Main Python script
│── students.yaml    # YAML file containing student data
│── README.md        # Project documentation
```

## Example YAML Format
```yaml
students:
  - name: Alice
    age: 21
    major: Computer Science
    gpa: 3.8
  - name: Bob
    age: 22
    major: Mathematics
    gpa: 3.5
```

## Screenshots
### 1. Setting up the environment
![Setup Screenshot](Screenshot from 2025-04-02 20-52-07.png)

### 2. Running the application
![Execution Screenshot](Screenshot from 2025-04-02 20-52-30.png)

## License
This project is licensed under the MIT License.

## Contributing
Contributions are welcome! Feel free to submit a pull request.

## Author
[Maanav Singh](https://github.com/yourusername)

