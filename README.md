# Student Information System

This project contains Java classes implementing a student information system, including classes for representing dates, names, students, and a main class to demonstrate their usage.

## Date Class

### File: Date.java

#### Properties:
- `year`: Represents the year.
- `month`: Represents the month.
- `day`: Represents the day.

#### Methods:
- `getYyMmDd()`: Returns the date in the format "yyyy-mm-dd".
- Accessor and mutator methods for `year`, `month`, and `day`.

## Name Class

### File: Name.java

#### Properties:
- `firstName`: Represents the first name.
- `lastName`: Represents the last name.

#### Methods:
- `getFullName()`: Returns the full name.
- `getInitials()`: Returns the initials.
- Accessor and mutator methods for `firstName` and `lastName`.

## Student Class

### File: Student.java

#### Properties:
- `name`: A `Name` object representing the student's name.
- `studentNumber`: Represents the student number.
- `dateOfBirth`: A `Date` object representing the date of birth.
- `graduationStatus`: Represents whether the student has graduated.

#### Methods:
- `getName()`: Returns the `Name` object.
- `getStudentNumber()`: Returns the student number.
- `getDateOfBirth()`: Returns the `Date` object.
- `isGraduated()`: Returns true if the student has graduated, false otherwise.
- `setGraduationStatus(boolean status)`: Updates the graduation status.

## Main Class

### File: Main.java

Contains the `main` method to create two `Student` objects and print their information.

### Sample Output:

```java
Tiger Woods (T.W.) (st # A00123456) was born on 1975-12-30. The student has graduated.
Bill Gates (B.G.) (st # A00987654) was born on 1955-10-28. The student has not graduated.
```

## How to Run

Compile the Java files and run the `Main` class.

```bash
javac Date.java Name.java Student.java Main.java
java Main
```

This will execute the `main` method and print the student information as described above.

