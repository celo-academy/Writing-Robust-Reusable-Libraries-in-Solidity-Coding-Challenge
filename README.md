## Introduction

Solidity is the primary language for writing smart contracts on blockchain platforms such as Celo. Libraries in Solidity offer a way to create reusable code that can be invoked from a contract. This challenge will test your ability to write a robust and reusable library in Solidity.

Problem Statement

Develop a Solidity library for handling common array operations with the following requirements:

1. The library should provide a function to find the index of an element in an array.
2. The library should have a function to check if an element exists in the array.
3. It should include a function to remove an element from an array by its value.
4. The library should also have a function to remove an element from an array by its index.
5. It should contain a function to insert an element at a specific position in the array.
6. The library should be designed to work with arrays of `address` type.

## Hints

- Use `library` keyword in Solidity to define your library.
- Utilize `for` loops for traversing and manipulating the array.
- You can use the `delete` keyword in Solidity to remove an element from an array.
- Remember, arrays in Solidity are zero-indexed.

## Evaluation Criteria

- **Correctness**: The library should compile without errors and satisfy all requirements.
- **Readability**: The library's code should be well-structured, with clear comments for each function.
- **Testability**: You should provide examples of how to test each function of the library.

Please note, this challenge primarily tests code reuse and doesn't cover important aspects like gas efficiency, security, or use of external libraries, which would be vital for real-world applications.

To deepen your understanding of Celo smart contracts and Solidity, consider reading through the Celo and Solidity tutorials.

## Submission

Please provide a link to your PR on GitHub, including your robust, reusable library. Also include any notes, comments, or design choices you think are important for understanding your code. Lastly, provide a brief explanation of how to test each function in the library.
