Navigate to the Project Directory
Make sure you are in the directory where you want to use Rustlings. For example:

```
cd D:\Programming\Rust\SolanaBootcamp\rustlings_project
```

Initialize Rustlings
If you haven't initialized Rustlings yet, run:
```rustlings init```

This command creates a rustlings/ directory containing the exercises.

Enter the Rustlings Directory
Change to the newly created rustlings directory:
```cd rustlings```

Run Rustlings
To start working on exercises, run:
```rustlings```
This will show you the list of exercises to complete.

Check for Hints
If you encounter a problem and need hints, you can run:
```rustlings hint <exercise_name>```
For example, for the variable exercise:
```rustlings hint variables3```

## Compile and Run
You can compile and run the project directly using:
```cargo run```
Ensure that you are in the exercise file's directory.

## Handling Common Errors

Macro Errors: If you see an error like cannot find macro, check the spelling of the macro. For example, use println!
instead of printline!.
Variable and Constant Declaration Errors: Remember:
Use let for mutable variables.
Use const for immutable constants and always provide a type annotation.

## Exit Rustlings
When you're done with the exercises or want to quit, you can simply exit the terminal or stop the Rustlings program.

Example of an Error and Fix

Error:
error: cannot find macro printline in this scope

Fix: Change printline! to println!:
```println!("Hello world!");```

## Summary
Using Rustlings helps you learn Rust effectively through practical exercises. Make sure to initialize it properly and
remember the key commands for hints and navigation. If you run into errors, check for typos and follow the guidance
provided by the Rust compiler.

# Installing Rustlings

We have a customised version of rustlings

1. Make sure you have rust installed
2. In this directory run

`cargo install --force --path .`

## Doing exercises

Run

`rustlings homework n`
Where n is the number of the homework you are doing, i.e.

`rustlings homework 5` 



