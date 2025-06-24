# Java Course

## System Requirements
- Java Development Kit
 ![alt text](image.png)

- Integrated Development Environment
  - IntelliJ is used here

### Getting Started with Main
#### Template
    public class Main {
        public static void main(String[] args){
            //write code in here
        }
    }


### Printing to Console Window
    System.out.println("I like pizza!);

### Variables

❎ variable = reusable container for a value. A variable behaves as if it was the value it contains.

🟥 Primitive = simple value stored directly in memory (stack)

🟦 Reference = memory address (stack) that points to the (heap)

| 🟥 Primitive | 🟦 Reference |
| ------ | ----------- |
| int   | string |
| double | array |
| char    | object |
| boolean    |  |

#### Steps to creating a variable.
1. Declaration
2. Assignment
#####
    //code
    int age; // declaration
    System.out.println(age); // gives error

    int age = 30.5;
    System.out.println(age); // ok

