## Project Description
This project is an AirBnB clone aimed at providing a platform for users to list, search, and book accommodations. It allows property owners to list their spaces and for users to search and book these spaces for their desired dates.

## Command Interpreter Description
The command interpreter is a tool built to interact with the AirBnB clone backend. It allows users to perform various actions such as creating, updating, deleting, and searching for accommodations, users, and bookings. 

### How to Start It
To start the command interpreter, follow these steps:
1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Run the command `./console.py` to start the interpreter.

### How to Use It
Once the command interpreter is running, you can use the following commands:
- `create <class>`: Create a new instance of a specified class.
- `show <class> <id>`: Show details of a specified instance.
- `destroy <class> <id>`: Delete a specified instance.
- `all <class>`: Show all instances of a specified class, or all instances if no class is specified.
- `update <class> <id> <attribute> <value>`: Update the attribute of a specified instances
## Examples
Here are some examples of how to use the command interpreter:

- Create a new user:
```
(create) user
```
- Show details of a specific accommodation:
```
(show) place 1234-5678
```
- Delete a user:
```
(destroy) user 9876-5432
```
- Show all bookings:
```
(all) booking
```
- Update the price of an accommodation:
```
(update) place 1234-5678 price 150
```

## Branches and Pull Requests
We utilize branches and pull requests on GitHub to organize our work efficiently. Each feature or bug fix is developed on its own branch, and pull requests are created when the work is ready to be reviewed and merged into the main branch. This workflow helps us collaborate effectively and maintain a clean codebase.
