# adminProject
This Java program generates JSON data representing repository statistics.

## Code Quality Analysis
During the development process, I employed PMD, a source code analyzer, to ensure adherence to coding standards and identify potential issues in my Java code. PMD helped me enforce best practices and maintain code quality throughout the project.

## How to Compile and Run

To compile and run this program, you need to have Java installed on your system. Follow these steps:

1. **Compile the Java Program**: Open your terminal or command prompt, navigate to the directory containing `adminProject.java`, and compile it using the following command:
2. **Run the Program**: After compiling the program, execute the following command to run it:
3. **View the Output**: Once the program finishes running, the JSON output will be displayed in the console.

## Sample Output

```json
{
"location": "/a/b/c",
"stat_of_repository": {
 "number_of_commits": 101,
 "avg_of_num_java_files": 30.2,
 "avg_of_num_warnings": 193.2
},
"stat_of_warnings": {
 "AbstractClassWithoutAbstractMethod": 1908,
 "AvoidReassigningCatchVariables": 2020
}
}

